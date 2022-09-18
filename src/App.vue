<template>
  <v-app>
    
    <Menu />

    <Bar />
    
    <v-content>
      <Carousel />
    </v-content>

    <Footer />
  </v-app>
</template>

<script>
import Footer from './Footer'
import Menu from './Menu'
import Carousel from './Carousel'
import Bar from './Bar.vue';

export default {  
  components: { Footer, Menu, Carousel, Bar },
  data() {

  }
}
</script>
