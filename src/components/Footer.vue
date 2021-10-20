<template>
<!-- <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M12 2C6.486 2 2 6.486 2 12s4.486 10 10 10 10-4.486 10-10S17.514 2 12 2zM4 12c0-.899.156-1.762.431-2.569L6 11l2 2v2l2 2 1 1v1.931C7.061 19.436 4 16.072 4 12zm14.33 4.873C17.677 16.347 16.687 16 16 16v-1a2 2 0 0 0-2-2h-4v-3a2 2 0 0 0 2-2V7h1a2 2 0 0 0 2-2v-.411C17.928 5.778 20 8.65 20 12a7.947 7.947 0 0 1-1.67 4.873z"></path></svg> -->
<footer id="contacto">
    <div class="contenedor-footer">
        <div class="contacto-us">
            <h2 class="brand">Municipalidad de Las Lomitas</h2>
            <p>Contacto:128748465359895 </p>
            <p>Direccion:------------- </p>
            <p>Email: laslomitas@gmail.com</p>
        </div>
        <div class="social-media">
            <a href="/" class="social-media-iconos">
            <i class="pi pi-facebook"></i>
            </a>
            
            <a href="/" class="social-media-iconos">
            <i class="pi pi-twitter"></i>
            </a>

            <a href="/" class=social-media-iconos>
           
              </a>
        </div>
    </div>
    <div class="line"></div>

</footer>

</template>

<style>
footer{
    background: rgba(145, 199, 200, 0.667);
    padding-bottom: 0.1px;
}
.contenedor-footer{
     text-align:center;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding-top: 10px;
    padding-bottom: 10px;
}
/* .contacto-us{
    width: 40px;
    color: rgb(20, 19, 19); */

 .brand{
    font-weight: 500;
    font-size: 40px;
    justify-content:center;
    
    
    
} 
 
 .social-media{
     width: 50%;
     display: flex;
     justify-content:center;
 }

 .social-media-iconos{
     display: inline-block;
     margin-left: 20px;
     width: 60px;
     height: 60px;
     border: 1px solid rgb(10, 1, 1);
     border-radius: 50%;
     text-align: center;
     color: #fff;
 }

 .social-media-iconos:hover{
     background: #fff;
     color: #0f0303;
 }

 .social-media-iconos i{
     font-size: 30px;
     line-height: 60px;
 }
 .line{
     width: 90%;
     max-width: 1200px;
     margin: auto;
     height: 2px;
     background: #fff;
     margin-bottom: 60px;
 }

</style>