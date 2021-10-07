<template>
  
   <div class="caja">
      <img src="../assets/cabecera1.png" >
   </div>     
    
   
  
</template>

<script>
export default {
  name: 'ImgCabecera',
  props: {
    msg: String
  }
}
</script>


<style >
.caja{
 display: flex;
 height: 250px;
 
  
 
}

.caja div{
  flex: 1;
  display: flex;
} 

.caja img{
  object-fit: cover;
}

</style>