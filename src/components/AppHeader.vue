<script>
import SlideShow from './Header/SlideShow.vue';
import BannerHeader from './Header/BannerHeader.vue';
export default {
  data() {
    return {
    };
  },
  components: {
    SlideShow,
    BannerHeader
  }

}
</script>

<template>
    <header>
      <nav>
        <div id="add-envato" class="d-flex justify-content-between align-items-center">
          <img class="col-6" id="logo-envato-market" src="../assets/fable-img/images/envato_market-a5ace93f8482e885ae008eb481b9451d379599dfed2486.svg" alt="envato-market">
          <button>
            Buy now
          </button>
        </div>
        <div class="my-container navbar p-0">
          <div class="row d-flex justify-content-between g-0">
            <div id="logo-fable" class="col-2">
              <img src="../assets/fable-img/images/logo.png" alt="">
            </div>
            <div class="icon-nav col-8 d-flex justify-content-end g-0">
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/home.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/home-2.png" alt="">
                <p>Home</p>
              </div>
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/document.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/document-2.png" alt="">
                <p>Pages</p>
              </div>
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/printer.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/printer-2.png" alt="">
                <p>Blog</p>
              </div>
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/cart.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/cart-2.png" alt="">
                <p>Shop</p>
              </div>
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/lab.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/lab-2.png" alt="">
                <p>Shortcodes</p>
              </div>
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/chat.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/chat-2.png" alt="">
                <p>Support</p>
              </div>
              <div class="link-nav col-1 d-flex flex-column justify-content-center align-items-center align-self-center g-0">
                <img class="icon-nav-img" src="../assets/fable-img/envelope.png" alt="">
                <img class="icon-nav-img-white" src="../assets/fable-img/envelope-2.png" alt="">
                <p>Contact</p>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </header>

    <SlideShow />
    <BannerHeader />
</template>

<style lang="scss" scoped>
 nav{
  box-shadow: 0 0 15px 0 #262626dc;
  background-color: white;
  position: sticky;
  top: 0;
}

/*Add Envato*/
#add-envato{
  height: 60px;
  padding: 20px 15px;
  background-color: #262626;
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


.navbar{
  height: 125px;
}

.navbar > .row{
 width: 100%;
}

#logo-fable{
  width: 180px;
}

.icon-nav{
  cursor: pointer;
}

.link-nav{
  width: 110px;
  height: 125px;
}

.icon-nav-img{
  width: 35px;
  margin-bottom: 10px;
}

.icon-nav-img-white{
  display: none;
  width: 35px;
  margin-bottom: 10px;
}

.link-nav > p{
  font-size: 18px;
  font-weight: 300;
  color: #56509F;
}

.nav-active{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  align-self: center;
  height: 125px;
  background-color: #FE6500;
  padding: 10px;

    p{
      color: white;
    }
}

.link-nav:hover{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  align-self: center;
  height: 125px;
  background-color: #FE6500;
  padding: 10px;

    p{
      color:white;
    }
    img:first-of-type{
      display: none;
    }
    img:last-of-type{
      display: flex;
    }
}



</style>