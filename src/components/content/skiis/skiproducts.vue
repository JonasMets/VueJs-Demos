<template>
  <div class="container mt-5">
    <!--Section: Content-->
    <section class="dark-grey-text text-center">
      <!-- Section heading -->
      <h3 class="font-weight-bold mb-4 pb-2">Our Products</h3>
      <!-- Section description -->
      <p
        class="grey-text w-responsive mx-auto mb-5"
      >The best in the world !</p>

      <!-- Grid row -->
      <div class="row">
        <!-- loopar productTemplate antal gånger som det finns objekt i products   -->
        <!--                                  :product="product" skickar in objektet i productTemplate som en props-->
        <productTemplate v-for="(product,index) in products" :key="index" :product="product"/>
        
        
      </div>
      <!-- Grid row -->
    </section>
    <!--Section: Content-->
  </div>
</template>

<script>
import productTemplate from './productTemplate';

export default {
  components:{
    productTemplate
  },
  data(){
    // mydemo1\public\images\ThorSki_6.png 
    return{
      products:[
        {category:"Ski",name:"Lightning",price:"$800",badge:"new",
        image:"images/ThorSki_6.png",style:'width: 60px'},
        {category:"Ski",name:"Lightning Pro",price:"$1000",badge:"new",
        image:"images/ThorSki_6.png",style:'width: 60px'},
        {category:"Ski",name:"Mjoelner",price:"$1000",badge:"new",
        image:"images/Test2.png",style:'width: 60px'},
        {category:"Ski",name:"Mjoelner Pro",price:"$1200",badge:"new",
        image:"images/Test2.png",style:'width: 60px'}
        
      ]
    }
  }
};
</script>

<style>
/* .imgsize{
  width: 160px;
} */
</style>