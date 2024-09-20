<script>
export default {
  data() {
    return {
    };
  }

}
</script>

<template>
    <header>
      <div id="add-envato" class="">
        <img class="col-6" id="logo-envato-market" src="../assets/fable-img/images/envato_market-a5ace93f8482e885ae008eb481b9451d379599dfed2486.svg" alt="envato-market">
        <button>
          Buy now
        </button>
      </div>
      <nav>
        <div class="my-container navbar">
          <div id="logo-fable">
            <img src="../assets/fable-img/images/logo.png" alt="">
          </div>
          <div class="icon-nav">
            <div class="link-nav">
              <img class="icon-nav-img" src="../assets/fable-img/home.png" alt="">
              <p>Home</p>
            </div>
            
          </div>
        </div>
      </nav>
    </header>
</template>

<style scoped>

/*Add Envato*/
#add-envato{
  height: 60px;
  padding: 20px 15px;
  background-color: #262626;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

#logo-envato-market{
  width: 150px;
}

#add-envato > button {
  width: 90px;
  height: 35px;
  font-size: 14px;
  padding: 5px;
  color: white;
  border: none;
  border-radius:5px;
  background-color: #8bc045;
}

#add-envato > button:hover {
  width: 90px;
  height: 35px;
  font-size: 14px;
  padding: 5px;
  color: white;
  border: none;
  border-radius:5px;
  background-color: #82B440;
}


/*NAVBAR*/
nav{
  height: 150px;
  border: 1px solid black;
}

.navbar{
  display: flex;
}

#logo-fable{
  width: 200px;
}

.icon-nav{
  display: flex;
  align-items: center;
}



.icon-nav-img{
  width:50px;
  margin-bottom: 10px;
}

.link-nav > p{
  font-size: 18px;
  font-weight:bold;
  color: #56509F;
}
</style>