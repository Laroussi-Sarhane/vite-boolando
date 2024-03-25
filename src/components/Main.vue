<script>
import productcard from './partials/productcard.vue';
import products from '../data/products'; 

export default{
  components:{
    productcard,
  },
  data(){
    return{
      products,
      productsArray: null
    }
  },
  mounted(){
    this.productsArray = this.products.products;
    console.log(this.products);
  }

}

</script>

<template>

  
  
  <main>
    
    <div class="contenitore">
     <productcard v-for="card in productsArray" 
     :key="card.id"
     :cardObj="card"
     />
     

    
    
   </div>
  </main>
 

</template>

<style lang="scss" scoped>
.contenitore{
  display: flex;
  flex-wrap: wrap;

}




</style>