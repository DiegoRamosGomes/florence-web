<template>
  <div id="app">
    <Header/>
    <Banner/>
    <section class="content">
      <TopTreatments />
    </section>
  </div>
</template>

<script>

import Header from "@/components/Header/Header";
import Banner from "@/components/Banner/Banner";
import TopTreatments from "@/components/Treatments/TopTreatments";

export default {
  name: 'App',
  components: {
    TopTreatments,
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

.content {
  margin: 0 $default-side-sizing;
}

button, .btn {
  height: 40px;
  border-radius: 50px;
  background-color: $blue;
  border: none;
  color: $white;
  font-weight: bold;
}
</style>
