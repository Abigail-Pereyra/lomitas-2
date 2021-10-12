<template>
  <section class="galeria" id="fotos">
    <div class="contenedor-galeria">
      <h2 class="subtitulo">Galeria</h2>
      <div class="contenedor-galeria">
        <img src="../assets/la-lomita09.png" alt="" class="img-galeria">
        <img src="../assets/foto2.png" alt="" class="img-galeria">
        <img src="../assets/foto3.png" alt="" class="img-galeria">
        <img src="../assets/foto4.png" alt="" class="img-galeria">
        <img src="../assets/foto6.png" alt="" class="img-galeria"> 
       
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Galeria',
  props: {
    msg: String
  }
}
</script>

<style>
.galeria{
  background: #f2f2f2;

}

.contenedor-galeria{
  display:flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
}

.img-galeria{
  width: 30%;
  display: block;
  margin-bottom: 15px;
  box-shadow: 0 0 6px rgba(0, 0, 0, .6);
  cursor: pointer;
  

  
}
/* .agregar-imagen{
  width: 60%;
  border-radius:10px;
}
.close{
  position: absolute;
  top: 15px;

} */

</style>