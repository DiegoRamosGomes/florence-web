<template>
  <div id="app">
    <Header/>
    <Banner/>
    <section class="main-content">
      <TopTreatments />
    </section>
    <MagrissimaProgram />
  </div>
</template>

<script>

import Header from "@/components/Header/Header";
import Banner from "@/components/Banner/Banner";
import TopTreatments from "@/components/Treatments/TopTreatments";
import MagrissimaProgram from "@/components/FeaturedInfo/MagrissimaProgram";

export default {
  name: 'App',
  components: {
    MagrissimaProgram,
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

.main-content {
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
