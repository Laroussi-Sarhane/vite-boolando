<script>

export default{
  data(){
    return{

    }
  }

}

</script>

<template>

  <header>
   
    <div class="container d-flex justify-content-between py-3 ">

      <div>
        <ul class=" d-flex ">
          <li><a href="#">uomo</a></li>
          <li><a href="#">donna</a></li>
          <li><a href="#">bambino</a></li>
          
        </ul>
      </div>

      <div>
        <img src="../assets/img/boolean-logo.png" alt="boolean-logo.png">
      </div>

      <div>
        <ul>
          <li></li>
          <li></li>
          <li></li>

        </ul>
      </div>


    </div>
  </header>
 

</template>

<style lang="scss" scoped>

header{
  height: 70px;
  background-color: orange;
  display: flex;
  ._contenitore{
    display: flex;
    justify-content: center;
    align-content: center;
  }
}
.links{
  list-style: none;
  padding: 10px;
  }
li{
  list-style: none;
  a{
    color: black;
    padding: 10px;
    text-decoration: none;
    font-weight: bolder;
    &:hover{
      text-decoration: underline;
    }
  }
  
}
.icons{
  display: flex;

}
img{
  width: 180px;
  
}




</style>