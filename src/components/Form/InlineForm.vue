<template>
  <form :action="this.href" class="component-inline-form">
    <slot/>
  </form>
</template>

<script>
export default {
  name: "InlineForm",
  props: {
    href: {
      type: String,
      required: true,
    }
  },
  components: {}

}
</script>

<style lang="scss" scoped>
@import "src/assets/styles/variables";

.component-inline-form {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;

  input {
    height: $input_height;
    width: 30%;
    max-width: 180px;
    border: 1px solid $secondary_pink;
    border-radius: 5px;
    padding: 0 10px;

    &:focus-visible {
      outline: none;
    }
  }

  button {
    width: 160px;
  }
}
</style>