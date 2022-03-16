<template>
  <div class="content">
    <SectionTitle title="Programa Magrissima"/>
    <div class="cards">
      <FeaturedCardItem title="Tratamento Facial" text="Não podemos nos esquecer de cuidar da nossa maior e mais importante ferramenta para cumprir as atividades do dia a dia: o nosso corpo." />
      <FeaturedCardItem title="Tratamento Facial" text="Não podemos nos esquecer de cuidar da nossa maior e mais importante ferramenta para cumprir as atividades do dia a dia: o nosso corpo." />
      <FeaturedCardItem title="Tratamento Facial" text="Não podemos nos esquecer de cuidar da nossa maior e mais importante ferramenta para cumprir as atividades do dia a dia: o nosso corpo." />
      <FeaturedCardItem title="Tratamento Facial" text="Não podemos nos esquecer de cuidar da nossa maior e mais importante ferramenta para cumprir as atividades do dia a dia: o nosso corpo." />
      <FeaturedCardItem title="Tratamento Facial" text="Não podemos nos esquecer de cuidar da nossa maior e mais importante ferramenta para cumprir as atividades do dia a dia: o nosso corpo." />
      <FeaturedCardItem title="Tratamento Facial" text="Não podemos nos esquecer de cuidar da nossa maior e mais importante ferramenta para cumprir as atividades do dia a dia: o nosso corpo." />
    </div>
  </div>
</template>

<script>
import SectionTitle from "@/components/Heading/SectionTitle";
import FeaturedCardItem from "@/components/Card/FeaturedCardItem";

export default {
  components: {FeaturedCardItem, SectionTitle}
}
</script>

<style lang="scss" scoped>
@import "src/assets/styles/variables";

.content {
  background-color: $light_pink;
  margin: 0;
  padding: 0 $default-side-sizing 70px;

  .cards {
    display: grid;
    grid-template-columns: auto auto auto;
    gap: 70px 5%;
    justify-content: center;
    margin-top: 30px;
  }
}
</style>