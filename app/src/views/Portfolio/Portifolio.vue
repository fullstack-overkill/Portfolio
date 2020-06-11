<template>
  <div class="page-home">
    <div class="header-aling">
      <Header/>
    </div>
    <div class="main-aling">
      <main class="Conteudo portifolio-container">
          <PortCard/>
      </main>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header/Header.vue";
import PortCard from "../../components/PortCard/PortCard.vue";

export default {
  name: 'Portifolio',
  data() {
    return {
      Logo:"C </>"
    }
  },
  components: {
    Header,
    PortCard,
  }
}
</script>

<style lang="stylus">
  @import '../../assets/styl/config.styl';
  @import '../../assets/styl/helpers.styl';
  @import 'Portfolio.styl';
</style>
