<template>
<main>
    
    <section class="contenedor">
        <div class="cont-secion">
        <h2>Tramites en linea</h2> 
        <Button label="Submit" class="p-button-text" />
        <ul><button>Pago tazas municipales2</button></ul>
        <ul><button>Pago tazas municipales3</button></ul>
         </div>


    
        <div class="cont-secion">
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
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-wrap: wrap;
 


}

.cont-seciones{
  width: 30%;
  text-align: block;
  margin: 0 auto;
}


</style>