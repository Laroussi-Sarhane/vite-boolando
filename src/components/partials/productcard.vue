<script>

export default{
   props:{
    frontImage: String,
    backImage: String,
    brand: String,
    name: String,
    price: String
   }
  }



</script>

<template>

<div class="_card container  d-flex ">

  <div class="product">

<div class="first">
  <img class="img" src="../assets/img/1.webp" alt="webp">
</div>
<div class="hearts"> <span id="cuore">&hearts;</span>
</div>

<div class="second">
  <img class="img" src="../assets/img/1.webp" alt="webp">
</div>
<div class="discount">-50%</div>

<div class="sostenibility">sostenibilità</div>

<p class="levis">levi's</p> 
 <strong>RELAXED FIT TEE UNISEX</strong> 
<div class="prezzo">
<span>14.99</span> <span class="prezzo-scontato">29.99</span> 
</div>

</div>
  
</div>
 
 

</template>

<style lang="scss" scoped>
._card{
  width: 33%;
 
}

</style>