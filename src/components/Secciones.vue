<template>
<main>
    
    <section class="contenedor">
        <div>
        <h2>Tramites en linea</h2>
       <ul><button>Pago tazas municipales</button></ul>
        <ul><button>Pago tazas municipales2</button></ul>
        <ul><button>Pago tazas municipales3</button></ul>
         </div>
   

    
        <div class="">
        <h2>Noticias</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus qui at quas placeat iste architecto porro impedit officia voluptates omnis ad blanditiis fugit veritatis nobis, debitis natus laborum suscipit. Quod?</p>
        <ul><button>mas</button></ul>
        
       
         </div>

    
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
  width: 90%;
  max-width: 1200px;
  overflow: hidden;
  margin: auto;
  padding: 60px 0;


}

p{
  overflow: auto;
}

button{
  padding: 20px;
  background: cyan;
  transition:  0.5s;
}

button:hover{
  padding: 20px;
  background: darkcyan;
}
</style>