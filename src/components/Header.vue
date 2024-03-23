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
   
    <div class=" _contenitore contaier d-flex  ">

      <div class="links ">
        <nav>
          <ul class="d-flex">
            <li>
              <a href="#">Uomo</a>
            </li>
            <li>
              <a href="#">Donna</a>
            </li>
            <li>
              <a href="#">Bambino</a>
            </li>
          </ul>
        </nav>
      </div>

      <div class="icons">
        LOGO
      </div>

      <div>
        <div>
           icon 1
        </div>

        <div>
          icon 1

        </div>

        <div>
          icon 1

        </div>

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