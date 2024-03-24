<script>

export default{
  data(){
    return{

    }
  }

}

</script>

<template>
  <footer>
    <div class="container d-flex justify-content-between ">

      <div>
        bolean srl 
        <div>
          <p>boolean srl è una societa che rispetta la tua privacy</p>
        </div>

      </div>

      <div >puoi tovarci anche qui:

        <div>
          <ul class="d-flex">
            <li><i class="fa-brands fa-facebook"></i></li>
            <li><i class="fa-brands fa-x-twitter"></i></li>
            <li><i class="fa-brands fa-youtube"></i></li>
            <li><i class="fa-brands fa-instagram"></i></li>

          </ul>
          

        </div>

      </div>
     
    </div>
  </footer>
 

</template>

<style lang="scss" scoped>
footer{
  background-color: black;
  height: 90px;
}
div{
  color: white;
}
ul{
  display: flex;
  li{
    text-decoration: none;
    list-style: none;
    padding: 3px;
  }
}



</style>