<template>
     <nav>
      <ul class="menu-navegacion">
        <li><a href="#">SERVICIOS</a>
          <ul>
            <li><a href="">Impuestos</a></li>
            <li><a href="">Recoleccion de Residuos</a></li>
            <li><a href="">Alumbrado Publico</a></li>
            
          </ul></li>
  
        <li><a href="#">TURISMO</a>
          <ul>
            <li><a href="">Alojamiento</a></li>
            <li><a href="">Excursiones</a></li>
            <li><a href="">Gastronomia</a></li>
            <li><a href="">Telefono</a></li>
          </ul></li>

          <li><a href="#">TASAS Y CONTRUBUCIONES MUNICIPALES</a>
            <ul>
              <li><a href="">Pagos Online</a></li>
              <li><a href="">Consulta Resumen Deuda</a></li>
              <li><a href="">Impresion de Cuota Vigente</a></li>
              
            </ul></li>

            <li><a href="#">TRAMITES</a>
              <ul>
                <li><a href="">Consulta de Expedientes</a></li>
                <li><a href="">Habilitaciones Comerciales</a></li>
                <li><a href="">Turnos</a></li>
         
              </ul></li>

         
  </ul>
      
       </nav>
    
</template>
<script>
export default {
  name: 'MenuNav',
  props: {
    msg: String
  }
}
</script>


<style>
.menu{
  position: fixed;
  top: 30px;
  right: 30px;
  background: #fff ;
  width: 40px;
  height: 40px;
  cursor: pointer;
  border-radius: 10px;
  box-shadow: 0 0 6px black;

}

.menu-navegacion{
  position: fixed;
  top: 0;
  right: 0;
  width: 30vw;
  height: 100%;
  background-image: linear-gradient(-225deg, #DFFFCD 0%, #90F9C4 48%, #39F3BB 100%);
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  transition: transform .3s ease-in-out;
  transform: translate(110%);  
  box-shadow: 0 0 6px rgba(0, 0, 0, .5 );


}


.spread{
  transform: translate(0);
}

.menu-navegacion a{
  color:black;
  text-decoration: none;
}
</style>