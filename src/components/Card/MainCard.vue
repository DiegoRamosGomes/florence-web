<template>
  <div class="component-main-card">
    <img class="component-main-card__image" :src="this.img" alt="#">
    <h2 class="component-main-card__title">{{ this.title }}</h2>
    <p class="component-main-card__content">
      <slot />
    </p>
    <div class="component-main-card__action"><a :href="this.action">Conheça</a></div>
  </div>
</template>

<script>
export default {
  name: "MainCard",
  props: {
    img: {
      type: String,
    },
    title: {
      type: String,
      required: true
    },
    action: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
@import "src/assets/styles/variables";

.component-main-card {
  width: 100%;
  border: 1px solid $secondary_pink;
  border-radius: 5px;
  margin: 0 30px;

  &__title, &__content {
    padding: 0 15px;
  }

  &__title {
    color: $blue;
    text-align: center;
    font-size: 17px;
  }

  &__content {
    font-size: 15px;
  }

  &__action {
    text-align: center;
    margin-bottom: 15px;

    & a {
      color: $blue;
      text-decoration: none;
      font-weight: bold;
      font-size: 15px;
    }
  }

  &:first-of-type {
    margin: 0 30px 0 0;
  }

  &:last-of-type {
    margin: 0 0 0 30px;
  }

  &__image {
    width: 100%;
    height: 150px;
    object-fit: fill;
  }
}
</style>