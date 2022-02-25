<template>
  <button class="component-header-action">Agendamento</button>
</template>

<script>
export default {
  name: "HeaderAction"
}
</script>

<style lang="scss" scoped>
  @import "src/assets/styles/variables";

  .component-header-action {
    height: 40px;
    border-radius: 50px;
    width: 160px;
    background-color: $blue;
    border: none;
    color: $white;
    font-weight: bold;
  }
</style>