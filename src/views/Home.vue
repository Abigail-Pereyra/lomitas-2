<template>
  <div class="home">
    
    <Cabecera msg="Municipalidad de Las Lomitas"/>
    <ImgCabecera/>
    <MenuNav/>
    <Secciones/>
    <Noticias/>
    <Galeria msg="Galeria"/>
    <Carousel/>
    <Footer/>
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Cabecera from '@/components/Cabecera.vue'
import Secciones from '@/components/Secciones.vue'
import Galeria from '@/components/Galeria.vue'
import MenuNav from '@/components/MenuNav.vue'
import Footer from '@/components/Footer.vue'
import ImgCabecera from '@/components/ImgCabecera.vue'
import Noticias from '@/components/Noticias.vue'
import Carousel from 'primevue/carousel';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    Cabecera,
    Secciones,
    Galeria,
    MenuNav,
    Footer,
    ImgCabecera,
    Noticias,
    Carousel
  }
}
</script>
