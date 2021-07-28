<template>
  <div class="home">
       <!-- Page Preloder -->
    <!-- <div id="preloder">
        <div class="loader"></div>
    </div> untuk loader -->
    <Header/>
    <Carousel/>
    <Banner/>
    <Instagram/>
    <Partner/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Carousel from '@/components/Carousel.vue'
import Banner from '@/components/Banner.vue'
import Instagram from '@/components/Instagram.vue'
import Partner from '@/components/Partner.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    Header,
    Carousel,
    Banner,
    Instagram,
    Partner,
    Footer,
  }
}
</script>
