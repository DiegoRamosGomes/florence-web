<template>
  <div id="app">
    <Header/>
    <Banner />
  </div>
</template>

<script>

import Header from "@/components/Header/Header";
import Banner from "@/components/Banner/Banner";

export default {
  name: 'App',
  components: {
    Banner,
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
