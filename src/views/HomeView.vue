<template>
  <div class="home">
    <HeaderComponent/>
    <hero-section-component-vue/>
    <banner-section-component-vue/>
    <instagram-component-vue/>
    <partner-logo-component-vue/>
  <footer-component-vue/>

  </div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from '@/components/HeaderComponent.vue'
import HeroSectionComponentVue from '../components/HeroSectionComponent.vue'
import BannerSectionComponentVue from '../components/BannerSectionComponent.vue'
import InstagramComponentVue from '../components/InstagramComponent.vue'
import PartnerLogoComponentVue from '../components/PartnerLogoComponent.vue'
import FooterComponentVue from '../components/FooterComponent.vue'


export default {
  name: 'HomeView',
  components: {
    HeaderComponent,
    HeroSectionComponentVue,
    BannerSectionComponentVue,
    InstagramComponentVue,
    PartnerLogoComponentVue,
    FooterComponentVue
   
  }
}
</script>
