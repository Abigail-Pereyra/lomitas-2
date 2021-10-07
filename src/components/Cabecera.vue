<template>
  <div class="cabecera">
    <h1>{{ msg }}</h1>
     
    
   
  </div>
</template>

<script>
export default {
  name: 'Cabecera',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.cabecera{
  /* display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 800px;
  margin: 0 auto;
  background-color:#faaa; */
  font-size: 12px;
   background-color:rgba(145, 199, 200, 0.667);
   width: 100vw;
   height: 10vh;
   position: fixed;
   margin: -90px;

}
h1{
  /* display:flex;
  align-items: center;
  margin: 0%; */
  line-height: 2.5;
   font-family: Georgia, 'Times New Roman', Times, serif;
   font-weight: 200;
   
  

}

template{
 
  background-color: powderblue;
}

/* .caja{
 display: flex;
 height: 250px;
  
 
}

.caja div{
  flex: 1;
  display: flex;
} 

.caja img{
  object-fit: cover;
} */
</style>