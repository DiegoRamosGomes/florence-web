<template>
  <ul class="component-header-menu">
    <li class="component-header-menu__item">
      <a class="component-header-menu__item__link" href="#">Quem somos</a>
    </li>
    <li class="component-header-menu__item">
      <a class="component-header-menu__item__link" href="#">Procedimentos</a>
    </li>
    <li class="component-header-menu__item">
      <a class="component-header-menu__item__link" href="#">Equipe</a>
    </li>
    <li class="component-header-menu__item">
      <a class="component-header-menu__item__link" href="#">Contato</a>
    </li>
  </ul>
</template>

<script>
export default {
  name: "HeaderMenu"
}
</script>

<style lang="scss" scoped>
@import "../../assets/styles/variables";

.component-header-menu {
  display: flex;
  padding: 0;

  &__item {
    list-style: none;
    margin: 0 25px;

    &:first-of-type {
      margin: 0 25px 0 0;
    }

    &:last-of-type {
      margin: 0 0 0 25px;
    }

    &__link {
      color: $blue;
      text-decoration: none;

      &:focus-visible {
        outline: none;
      }
    }
  }
}
</style>