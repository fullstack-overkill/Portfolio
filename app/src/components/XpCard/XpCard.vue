<template>
  <div class="xp-card">
    <div class="card-img"><img src="../../assets/img/xp/cquantt.png" alt=""></div>
    <div class="card-content">
      <div class="content-title">jr Full Stack</div>
      <div class="content-desc">
          <div class="desc-place-name">Cquantt</div>
          <div class="desc-period">maio de 2019 - out de 2019</div>
          <div class="desc-city">Goiânia e Região</div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'XpCard',
  props: {
    Img: String,
    Title: String,
    Desc: String,
    CtaLink: String,
  },
  data() {
    return {

    }
  },

}
</script>

<style lang="stylus">
  @import '../../assets/styl/config.styl';
  @import '../../assets/styl/helpers.styl';
  @import 'XpCard.styl';
</style>
