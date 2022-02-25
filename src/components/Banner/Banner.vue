<template>
  <div class="component-banner">
    <img src="@/assets/banner.png" alt="Banner" class="component-banner__item">
  </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style lang="scss" scoped>
  .component-banner {
    &__item {
      width: 100%;
      max-height: 500px;
      object-fit: fill;
    }
  }
</style>