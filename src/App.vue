<template>
  <div id="app">
    <div class="header-bg">
      <svg class="bg-svg" xmlns="http://www.w3.org/2000/svg" viewBox="-300 0 950 270" >
        <path d="M-314,267 C105,364 400,100 812,279" fill="none" stroke="white" stroke-width="120" stroke-linecap="round"/>
      </svg>
      <Nav></Nav>
      <Header></Header>
    </div>
    <Features></Features>
    <Usability></Usability>
    <Services></Services>
    <Pricing></Pricing>
    <Download></Download>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import Nav from './components/Nav.vue';
import Header from './components/Header.vue';
import Features from './components/Features.vue';
import Usability from './components/Usability.vue';
import Services from './components/Services.vue';
import Pricing from './components/Pricing.vue';
import Download from './components/Download.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'app',
  components: {
    Nav,
    Header,
    Features,
    Usability,
    Services,
    Pricing,
    Download,
    Contact,
    Footer
  }
}
</script>

<style lang="scss">
@import "sass/main";
</style>