<template>
  <div class="port-card">
    <div class="card-img"><img v-bind:src="Img" alt=""></div>
    <div class="card-content">
      <div class="content-title">{{this.Title}}</div>
      <div class="content-desc">{{Desc}}</div>
      <div class="content-cta">Visitar</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'PortCard',
  props: {
    Img: String,
    Title: String,
    Desc: String,
    CtaLink: String,
  },
  data() {
    return {
      Logo:"C </>"
    }
  },

}
</script>

<style lang="stylus">
  @import '../../assets/styl/config.styl';
  @import '../../assets/styl/helpers.styl';
  @import 'PortCard.styl';
</style>
