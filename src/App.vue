<template>
 <div>
     <img class="image-header" alt="Imagen-header" src="../src/assets/image/image-header.jpg" >
     <Header/>
     <div class="figure">
       <img src="../src/assets/icon-arrow-down.svg" alt="arrow down">
     </div>
     
   <!-- <div id="main-container">
     <h2>Todo contenido</h2>
   </div> -->
 </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header.vue';
// import Main from './components/main.vue';
// import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    Header 
    // Main, 
    // Footer
  }
  // data() {
  //   return {
      /*Aqui van los elementos de javaScript, para que sea funcional*/
  //   }
  // },
}
</script>

<style>
:root{
  /* ## Colors */

/* ### Primary */

--Soft-red: hsl(7, 99%, 70%);
--Yellow: hsl(51, 100%, 49%);
--Dark-desaturated-cyan: hsl(167, 40%, 24%); /*(graphic design text)*/
--Dark-blue: hsl(198, 62%, 26%); /*(photography text) */
--Dark-moderate-cyan : hsl(168, 34%, 41%); /*(footer)*/

/* ### Neutral */

--Very-dark-desaturated-blue: hsl(212, 27%, 19%);
--Very-dark-grayish-blue: hsl(213, 9%, 39%);
--Dark-grayish-blue: hsl(232, 10%, 55%);
--Grayish-blue: hsl(210, 4%, 67%);
--White: hsl(0, 0%, 100%);
}

 *{
   box-sizing: border-box;
   margin: 0;
   font-size: 18px;
 }
 .image-header{
   width: 100%;
   position: absolute;
 }
 .figure{
   position: relative;
   display: flex;
   margin-top: 60px;
   justify-content: center;
}


 

</style>
