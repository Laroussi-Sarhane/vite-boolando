<script>


export default{
   props:{
   cardObj: Object
   },
   methods:{
    getPathImage(imageName){
      return new URL (`../../assets/img/${imageName}`, import.meta.url).href
    }
   }
  }



</script>

<template>

<div class="_card container  d-flex ">

  <div class="product container ">

<div class="first">
  <img class="img" :src="getPathImage(cardObj.frontImage)" :alt="cardObj.name ">
</div>
<div class="hearts"> <span id="cuore">&hearts;</span>
</div>

<div class="second">
  <img class="img" :src="getPathImage(cardObj.backImage)" :alt="cardObj.name ">
</div>
<div class="discount">-50%</div>

<div class="sostenibility">sostenibilità</div>

<p class="levis">{{ cardObj.brand }}</p> 
 <strong>{{ cardObj.name }}</strong> 
<div class="prezzo">
<span>{{ cardObj.price }}</span> <span class="prezzo-scontato">29.99</span> 
</div>

</div>
  
</div>
 
 

</template>

<style lang="scss" scoped>
._card{
  width: 33%;
}
#cuore{
  width: 20px;
  text-align: center;
  height: 20px;
}
.hearts{
  height: 40px;
  width: 40px;
  text-align: center;
  background-color: white;
  position: absolute;
  top: 10px;
  right: 0;
  color: black;
  
}
.discount{
  height: 30px;
  width: 60px;
  position: absolute;
  background-color: red;
  color: white;
  bottom: 100px;
  left: 0;
  text-align: center;
  margin-top: 20px;
}
.sostenibility{
  height: 30px;
  width: 115px;
  position: absolute;
  background-color:green;
  color: white;
  bottom: 100px;
  left: 65px;
  text-align: center;
  margin-top: 20px;

}
.sostenibility-last{
  height: 30px;
  width: 115px;
  position: absolute;
  background-color:green;
  color: white;
  bottom: 100px;
  left:0;
  text-align: center;
  margin-top: 20px;

}
.product{
 
  position: relative;
	cursor: pointer;
 
  width:33%;
 
  margin-bottom: 40px;
}

img{
  width: 100%;
}

.product .second{
  display: none;
  position: absolute;
  left: 0;
  top: 0;
	
  
  
}
.product:hover .second{
  display: block;
  
	position: absolute;
  
}
.levis{
  color: grey;
}
.prezzo{
  color: red;
}
.prezzo-scontato{
  color: black;
  text-decoration: underline;
}

</style>