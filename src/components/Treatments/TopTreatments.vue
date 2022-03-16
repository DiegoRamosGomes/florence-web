<template>
  <div class="content">
    <SectionTitle title="Top Tratamentos" />
    <div class="component-top-treatments">
      <MainCard action="#" title="Tratamento Facial"
                img="https://www.giolaser.com.br/wp-content/uploads/2021/02/img-card-tratamento-facial.jpg">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi aspernatur autem doloribus eos expedita,
        facilis, magnam maiores non praesentium provident, sequi tempora velit. Ad at harum, inventore nisi porro saepe.
      </MainCard>
      <MainCard action="#" title="Tratamento Facial"
                img="https://www.giolaser.com.br/wp-content/uploads/2021/02/img-card-tratamento-facial.jpg">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi aspernatur autem doloribus eos expedita,
        facilis, magnam maiores non praesentium provident, sequi tempora velit. Ad at harum, inventore nisi porro saepe.
      </MainCard>
      <MainCard action="#" title="Tratamento Facial"
                img="https://www.giolaser.com.br/wp-content/uploads/2021/02/img-card-tratamento-facial.jpg">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi aspernatur autem doloribus eos expedita,
        facilis, magnam maiores non praesentium provident, sequi tempora velit. Ad at harum, inventore nisi porro saepe.
      </MainCard>
      <MainCard action="#" title="Tratamento Facial"
                img="https://www.giolaser.com.br/wp-content/uploads/2021/02/img-card-tratamento-facial.jpg">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi aspernatur autem doloribus eos expedita,
        facilis, magnam maiores non praesentium provident, sequi tempora velit. Ad at harum, inventore nisi porro saepe.
      </MainCard>
    </div>
  </div>
</template>

<script>
import MainCard from "@/components/Card/MainCard";
import SectionTitle from "@/components/Heading/SectionTitle";

export default {
  name: "TopTreatments",
  components: {SectionTitle, MainCard}
}
</script>

<style lang="scss" scoped>
.component-top-treatments {
  display: flex;
  margin: 0 0 70px;
}
</style>