<template>
  <div class="page-home">
    <div class="header-aling">
      <Header/>
    </div>
    <div class="main-aling">
      <main class="Conteudo portifolio-container">
       
        <div 
            v-for="PortifolioItem in Portifolio" 
            :key="PortifolioItem"  
            class="card-list-item"
        >
            <PortCard
                :Img="PortifolioItem.img"
                :Title="PortifolioItem.title"
                :Desc="PortifolioItem.desc"
                :CtaLink="PortifolioItem.ctaLink"           
            />
        </div>  
      </main>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header/Header.vue";
import PortCard from "../../components/PortCard/PortCard.vue";

//Import de imagens
import img from "../../assets/img/test_img_card.png";

export default {
  name: 'Portifolio',
  data() {
    return {
      Logo:"C </>",
      Portifolio: [
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},

        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
        {img: img, title:"Loja virtual", desc:"Uma loja virtual para debuatantes", ctaLink:""},
      ]
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
