<template>
  <div class="comp-Header">
      <div class="logo">
        {{Logo}}
      </div>
      <nav class="Nav">
          <div class="Nav-page Selected">Home</div>
          <div class="Nav-page">skills</div>
          <div class="Nav-page">About</div>
          <div class="Nav-page">Experiences</div>
      </nav>
      <div class="btn-contato">
        Contato
      </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Header',
  data() {
      return {
          Logo:"C </>"
      }
  },
  components: {
  }
}
</script>

<style lang="stylus">
  @import '../../assets/styl/config.styl';
  @import '../../assets/styl/helpers.styl';
  @import 'Header.styl';
</style>
