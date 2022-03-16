<template>
  <h1 class="title">{{ this.title }}</h1>
</template>

<script>
export default {
  props: {
    title: {
      required: true,
      type: String
    }
  }
}
</script>

<style lang="scss" scoped>
@import "src/assets/styles/variables";

.title {
  text-align: center;
  color: $blue;
  margin: 70px 0;
  font-size: 50px;
}
</style>