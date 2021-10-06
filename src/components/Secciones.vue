<template>
<main>
    
    <section class="contenedor">
        <div>
        <h2>Tramites en linea</h2>
       <ul><button>Pago tazas municipales</button></ul>
        <ul><button>Pago tazas municipales2</button></ul>
        <ul><button>Pago tazas municipales3</button></ul>
         </div>
    </section>

    <section   class="contenedor">
        <div class="">
        <h2>Noticias</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus qui at quas placeat iste architecto porro impedit officia voluptates omnis ad blanditiis fugit veritatis nobis, debitis natus laborum suscipit. Quod?</p>
        <ul><button>mas</button></ul>
        
       
         </div>

    </section>
    <section class="contenedor">
        <div>
        <h2>Visita Nuestras Redes</h2>
       <ul><button>Facebook</button></ul>
        <ul><button>Twitter</button></ul>
        <ul><button>Instagram</button></ul>
         </div>
    </section>
   
</main>
</template>

<script>
export default {
  name: 'Secciones',
  props: {
    msg: String
  }
}
</script>

<style>
.contenedor{
  display: inline-block;
  padding:100px;
  text-align: center;

}

p{
  overflow: auto;
}

</style>