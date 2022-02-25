<template>
  <div class="component-header">
    <HeaderLogo/>
    <HeaderMenu/>
    <HeaderAction/>
  </div>
</template>

<script>
import HeaderLogo from "@/components/Header/HeaderLogo";
import HeaderMenu from "@/assets/HeaderMenu";
import HeaderAction from "@/components/Header/HeaderAction";

export default {
  name: "Header",
  components: {HeaderAction, HeaderMenu, HeaderLogo}
}
</script>

<style lang="scss" scoped>
@import "src/assets/styles/variables";

.component-header {
  display: flex;
  justify-content: space-between;
  margin: 0 ;
  padding: 27px $default-side-sizing;
  box-shadow: 0 2px 12px -7px black;
}
</style>