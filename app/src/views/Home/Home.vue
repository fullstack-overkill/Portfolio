<template>
  <div class="page-home">
    <div class="header-aling">
      <Header/>
    </div>
    <div class="main-aling">
      <main class="Conteudo">
        <div class="main-name">hey ! i'm  <strong class="Destaque">Christopher M</strong>.</div>
        <div class="main-sub">Full stack software Enginner.</div>
        <div class="main-desc">
          I am passionate about creating and developing software,
          I always try to improve myself and learn new things,
          my goal is to make the world a better place to live and
          bring information to everyone. I currently live in Goiânia Goiás
          and have experience in full stack development.
        </div>
        <div class="see-my-work">
          PORTFOLIO
        </div>
      </main>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header/Header.vue";

export default {
  name: 'Home',
  components: {
    Header,
  }
}
</script>

<style lang="stylus">
  @import '../../assets/styl/config.styl';
  @import '../../assets/styl/helpers.styl';
  @import 'Home.styl';
</style>
