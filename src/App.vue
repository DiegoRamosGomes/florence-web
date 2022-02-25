<template>
  <div id="app">
    <Header/>
    <Banner/>
    <section class="content">
      <ContactForm/>
    </section>
  </div>
</template>

<script>

import Header from "@/components/Header/Header";
import Banner from "@/components/Banner/Banner";
import ContactForm from "@/components/Home/ContactForm";

export default {
  name: 'App',
  components: {
    ContactForm,
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
