<template>
  <div class="comp-Header">
      <div class="logo">
        {{Logo}}
      </div>
      <nav class="Nav">
        <router-link to="/" class="Nav-page Selected">Home</router-link>
        <router-link to="/" class="Nav-page">skills</router-link>
        <router-link to="/" class="Nav-page">About</router-link>
        <router-link to="/experiences" class="Nav-page">Experiences</router-link>
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
