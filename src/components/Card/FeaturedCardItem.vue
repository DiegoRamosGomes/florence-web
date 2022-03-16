<template>
  <div class="featured-card-item">
    <img class="featured-card-item__avatar" :src="img" alt="Imagem do tratamento" />
    <h3 class="featured-card-item__title">{{ this.title }}</h3>
    <p class="featured-card-item__text">{{ this.text }}</p>
  </div>
</template>

<script>
export default {
  props: {
    title: { required: true },
    text: { required: true },
    img: { required: false, default: 'https://cdn.iconscout.com/icon/free/png-256/avatar-370-456322.png' }
  }
}
</script>

<style lang="scss" scoped>
@import "src/assets/styles/variables";

.featured-card-item {
  background-color: $white;
  border: 1px solid $secondary_pink;
  border-radius: 5px;
  text-align: center;
  min-width: 250px;
  max-width: 300px;

  &__avatar {
    width: 120px;
    height: 120px;
    margin-top: -30px;
  }

  &__title {
    color: $blue;
    font-size: 15px;
    margin: 30px 0 15px;
  }

  &__text {
    margin: 0 15px 30px;
    font-size: 15px;
  }
}
</style>