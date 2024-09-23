<script>
const slidePath = '../src/assets/fable-img/images';

export default {
  data() {
    return {
      slideshow: [
        {
          id: 1,
          image: `${slidePath}gallery_07-690x506.jpg`
        },
        {
          id: 2,
          image: `${slidePath}gallery_01.jpg`
        },
        {
          id: 3,
          image: `${slidePath}gallery_08-690x506.jpg`
        }
      ],
      currentImg: 0
    };
  },
  methods: {
    nextSlide() {
        if(this.currentImg + 1 < this.slideshow.length) {
            this.currentImg++;
        }
        else {
            this.currentImg = 0;
        }
    },
    prevSlide () {
        if (this.currentImg > 0) {
            this.currentImg--;
        }
        else {
            this.currentImg = this.slideshow.length - 1;
        }
    },
    goToSlide(index) {
        this.currentImg = index;
    }
  }
}
</script>

<template>
  <section>
    <div class="my-container d-flex align-items-center">
      <div class="row py-5">

        <div>
          <button class="button-static active">Overview</button>
          <button class="button-static ">Our Mission</button>
        </div>

        <!--Overview-->
          <div class="overview w-100 col-6">

            <div>
              <div class="description-overview">
                <p>
                  Our philosophy is learning through play as we offer a stimulating environment for children.
                </p>
              </div>
              

              <div class="row d-flex align-items-center">
                
                <div class="col-3 icon-overview">
                  <img src="/src/assets/fable-img/images/clock_alt.png" alt="">
                </div>

                <div class="col-9">
                  <div>
                    <h4 class="title-overview">
                      Full Day Session
                    </h4>
                    <p class="text-overview">
                      Pulvinar est metro ligula blandit maecenas retrum gravida cuprum. Maecenas node estibulum.
                    </p>
                  </div>
                </div>

              </div>

              <div class="row d-flex align-items-center my-3">
                
                <div class="col-3 icon-overview">
                  <img src="/src/assets/fable-img/images/diagram_alt.png" alt="">
                </div>

                <div class="col-9">
                  <div>
                    <h4 class="title-overview">
                      Full Day Session
                    </h4>
                    <p class="text-overview">
                      Pulvinar est metro ligula blandit maecenas retrum gravida cuprum. Maecenas node estibulum.
                    </p>
                  </div>
                </div>

              </div>
            </div>
          </div>
      </div>
      <!--SLIDER-->
        <div class="my-container d-flex justify-content-end col-6 ">
          <div class="slideshow w-100">
            <div class="row">
              <div v-for="(slide, index) in slideshow" :key="slide.id" class="slide col-12" :class="{ active: index === currentImg}" :style="{ backgroundImage: 'url(' + slide.image + ')' }">
                <img :src="slide.image" alt="">
              </div>
            </div>

            <div class="d-flex row">
              <div class="box-img g-0 col-4">
                <img src="/src/assets/fable-img/images/gallery_07-690x506.jpg" alt="">
              </div>
              <div class="box-img g-0 col-4">
                <img src="/src/assets/fable-img/images/gallery_01.jpg" alt="">
              </div>
              <div class="box-img g-0 col-4">
                <img src="/src/assets/fable-img/images/gallery_08-690x506.jpg" alt="">
              </div>
            </div>
          </div>
        </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
  section{
    background-color:#F5F5F5;
  }

  /*Button*/
  .button-static{
    font-size: 20px;
    background-color: rgba(255, 255, 255, 0);
    padding: 10px;
    border: none;
    border-bottom: 1px solid rgb(143, 143, 143);
    margin-right: 15px;
    margin-bottom: 25px;
    color:rgb(143, 143, 143);
  }
  .button-static:hover{
    background-color:#FE6500;
    padding: 10px;
    margin-right: 15px;
    margin-bottom: 25px;
    color:white;
    border: none;
  }

  .active{
    background-color:#FE6500;
    padding: 10px;
    margin-right: 15px;
    margin-bottom: 25px;
    color:white;
    border: none;
  }

  /*Card */
  .description-overview{
    color: #5E58A4;
    font-size: 35px;
    line-height: 40px;
    margin-bottom: 25px;
  }

  .icon-overview{
    display: flex;
    justify-content: center;
    align-items: center;
    width:70px;
    height:70px;
    border-radius: 50%;
    padding:15px;
    margin-bottom: 20px;
    margin-right: 15px;
    background-color: #FE6500;
  }

  .title-overview{
    font-size: 22px;
    color:#5E58A4;
  }

  .text-overview{
    font-size: 16px;
    color: grey;
  }

  /*BOX IMAGE */

  .slideshow{
    margin: 30px;
  }

  .box-img{
    width: 160px;
    height: 150px;
    margin: 0 5px;
  }

</style>