<script>
import productcard from './partials/productcard.vue';

export default{
  components:{
    productcard,
  }

}

</script>

<template>

  
  
  <main>
    
    <div class="contenitore">
     <productcard/>
     <productcard/>
     <productcard/>
     <productcard/>
     <productcard/>
     <productcard/>
    

    
    
   </div>
  </main>
 

</template>

<style lang="scss" scoped>
.contenitore{
  display: flex;
  flex-wrap: wrap;

}



</style>