<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>

import Header from "@/components/Header/Header";

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import './assets/styles/variables';

body {
  margin: 0;
}

#app {
  background-color: $white;
}
</style>
