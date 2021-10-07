<template>
  <header>
   <div class="header" >
     <!-- <img src= "../assets/cabecera1.png" alt=""> -->
   </div>     
    
   </header>
  
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
.header{
  height: 100vh;
  background-image: url("../assets/cabecera1.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
  background-position: center;

}

</style>