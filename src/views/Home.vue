<template>
  <div class="home">
    
    <Cabecera msg="Municipalidad de Las Lomitas"/>
    <ImgCabecera/>
    <MenuNav/>
    <Secciones/>
     <Carousel/>
    <Noticias/>
    <Galeria msg="Galeria"/>
   
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

<style>
 @media screen and (max-width:800px){
   .menu-navegacion{
     width: 50vh;
   }

   .contenedor{
     width: 80%;
     margin-bottom: 40px;
   }

   .img-galeria{
     width: 45%;
   }

   .footer-contect{
     justify-content: center;
   }

   .social-media{
     width: 95%;
     justify-content: space-evenly;
   }

   .social-media-iconos {
     margin-left:0;
   }

   .contacto-us{
     text-align: center;
     width: 80%;
     margin-bottom: 40px;
   }
 }

 /* @media screen and (max-width:500px){
   .menu-navegacion{
     width: 65vh;
   }

   .contenedor{
     width: 80%;
     margin-bottom: 40px;
   }

   .img-galeria{
     width: 45%;
   }

   .footer-contect{
     justify-content: center;
   }

   .social-media{
     width: 95%;
     justify-content: space-evenly;
   }

   .social-media-iconos {
     margin-left:0;
   }

   .contacto-us{
     text-align: center;
     width: 80%;
     margin-bottom: 40px;
   }
 } */
</style>
