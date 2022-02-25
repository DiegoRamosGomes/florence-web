<template>
  <div class="component-contact-form">
    <div class="component-contact-form__title">
      <h2>Agende uma avaliação</h2>
      <h3>GRATUITA</h3>
    </div>
    <InlineForm href="#">
      <input type="text" placeholder="Nome">
      <input type="text" placeholder="Email">
      <input type="text" placeholder="Telefone">
      <button type="submit">Agendar</button>
    </InlineForm>
  </div>
</template>

<script>
import InlineForm from "@/components/Form/InlineForm";

export default {
  name: "ContactForm",
  components: {InlineForm}
}
</script>

<style lang="scss" scoped>
  @import "src/assets/styles/variables";

  .component-contact-form {
    display: flex;
    margin: 70px 0;

    &__title {
      margin-right: 5%;

      h2, h3 {
        font-size: 1.25rem;
        margin: 0;
        text-align: center;
        color: $blue;
        width: 200px;

      }
    }
  }
</style>