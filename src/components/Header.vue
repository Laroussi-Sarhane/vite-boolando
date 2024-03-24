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

      <div>uomo donna baby</div>

      <div>
        <img src="../assets/img/boolean-logo.png" alt="boolean-logo.png">
      </div>

      <div>icone</div>


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
  }
  
}
.icons{
  display: flex;

}
img{
  width: 200px;
}




</style>