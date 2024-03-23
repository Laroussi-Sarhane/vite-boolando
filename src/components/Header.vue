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
  &:hover{
    text-decoration: underline;
  }
  a{
    color: black;
    padding: 10px;
  }
}
.icons{
  display: flex;

}




</style>