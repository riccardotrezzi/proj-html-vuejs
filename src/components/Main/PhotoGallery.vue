<script>

export default {
  data() {
    return {
    };
  }
  

}
</script>

<template>
  <section>
    <div>
      <div class="row d-flex">
        <div class="gallery col-4 g-0">
          <button class="circle-blu">
            <i class="fa-solid fa-plus"></i>
          </button>
          <img src="/src/assets/fable-img/images/gallery_01-690x506.jpg" alt="">
        </div>
        <div class="gallery col-4 g-0">
          <button class="circle-blu">
            <i class="fa-solid fa-plus"></i>
          </button>
          <img src="/src/assets/fable-img/images/gallery_02-690x506.jpg" alt="">
        </div>
        <div class="gallery col-4 g-0">
          <button class="circle-blu">
            <i class="fa-solid fa-plus"></i>
          </button>
          <img src="/src/assets/fable-img/images/gallery_03-690x506.jpg" alt="">
        </div>
        <div class="gallery col-4 g-0">
          <button class="circle-blu">
            <i class="fa-solid fa-plus"></i>
          </button>
          <img src="/src/assets/fable-img/images/gallery_04-690x506.jpg" alt="">
        </div> 
      </div>
    </div>

    <div id="banner-section" class="d-flex justify-content-between align-items-center">
      <div class="my-container w-100 d-flex justify-content-between align-items-center">
        <h2>
          See Our Kindergarten Photo Gallery!
        </h2>

        <button id="gallery-button">
            <span>view Gallery</span>
            <i class="fa-solid fa-chevron-right"></i>
        </button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

.gallery{ 
  width: calc(100% / 4);
  position: relative
}

.circle-blu{
  width: 110px;
  height:110px;
  border-radius: 50%;
  padding:20px;
  margin: auto;
  background-color:#57509fbf;
  border:none;
  color: white;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;

    i{
      font-size: 24px;
    }
}

#banner-section{
  height: 130px;
  background-image: url("/src/assets/fable-img/images/pattern.png");
  background-attachment: fixed;
}

h2{
    font-weight: 300;
    color: white;
    margin-right: 20px;
}

#gallery-button{
    width: 170px;
    height: 60px;
    padding: 10px;
    border: 2px solid white;
    background-color: rgba(255, 255, 255, 0);

    span {
        margin-right: 10px;
        text-transform: uppercase;
        color: white;
    }

    i{
        color: white; 
    }

}

#gallery-button:hover{
    width: 170px;
    padding: 10px;
    border: 2px solid white;
    background-color: #ffffff;

    span {
        margin-right: 10px;
        text-transform: uppercase;
        color:#56509F;
    }

    i{
        color: #56509F;
    }

}
</style>