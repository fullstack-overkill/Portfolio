<template>
  <div class="page-home">
    <div class="header-aling">
      <Header/>
    </div>
    <div class="main-aling">
      <main class="Conteudo">
        <XpCard/>
        <XpCard/>
        <XpCard/>
      </main>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header/Header.vue";
import XpCard from "../../components/XpCard/XpCard.vue";

export default {
  name: 'Experiences',
  data() {
    return {

    }
  },
  components: {
    Header,
    XpCard,
  }
}
</script>

<style lang="stylus">
  @import '../../assets/styl/config.styl';
  @import '../../assets/styl/helpers.styl';
  @import 'Experiences.styl';
</style>
