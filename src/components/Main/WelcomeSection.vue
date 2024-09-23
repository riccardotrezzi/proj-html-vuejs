<script>
import DataSlider from '../Main/DataSlider.vue';
import OverviewSection from '../Main/OverviewSection.vue';

export default {
  data() {
    return {
    };
  },
  components: {
    OverviewSection,
    DataSlider
  }

}
</script>

<template>

    <!--WELCOME SECTION-->
    <section class="m-5">
      <div class="my-container">
        <div id="title-section" class="d-flex flex-column align-items-center">
          <h1 class="open-sans-light">Welcome to Fable</h1>
          <p>Fable daycare, preschool, and kindergarten</p>
          <img class="m-3" src="/src/assets/fable-img/images/header_divider.png" alt="">
        </div>
        
        
        <div class="row">
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="circle-img-orange">
              <img src="/src/assets/fable-img/images/schoolbag_alt.png" alt="">
            </div>
            <h4 class="title-circle">Morbi Etos</h4>
            <p class="text-circle">Praesent interdum est gravida vehicula est node maecenas loareet morbi a dosis luctus novum est praesent.</p>
          </div>
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="circle-img-blu">
              <img src="/src/assets/fable-img/images/stroller_alt.png" alt="">
            </div>
            <h4 class="title-circle">Congue Gravida</h4>
            <p class="text-circle">Elipsis magna a terminal nulla elementum morbi elite forte maecenas est magna etos interdum vitae est.</p>
          </div>
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="circle-img-orange">
              <img src="/src/assets/fable-img/images/globe_alt.png" alt="">
            </div>
            <h4 class="title-circle">Maecenas Node</h4>
            <p class="text-circle">Praesent interdum est gravida vehicula est node maecenas loareet morbi a dosis luctus novum est praesent.</p>
          </div>
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="circle-img-blu">
              <img src="/src/assets/fable-img/images/bell_alt.png" alt="">
            </div>
            <h4 class="title-circle">Praesent Morbi</h4>
            <p class="text-circle">Elipsis magna a terminal nulla elementum morbi elite forte maecenas est magna etos interdum vitae est.</p>
          </div>
        </div>
      </div>
    </section>

    <OverviewSection />
    <DataSlider />
</template>

<style lang="scss" scoped>

#title-section{
  margin: 40px 0;

    h1{
      font-size: 3rem;
      color:#5E58A4;
    }
    .open-sans-light {
      font-family: "Open Sans", sans-serif;
      font-optical-sizing: auto;
      font-weight: 300;
      font-style: normal;
    }

    p{
      font-size: 1rem;
      color:grey;
    }
}

.circle-img-orange{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 170px;
  height:170px;
  border-radius: 50%;
  padding:15px;
  margin-bottom: 20px;
  background-color: #FE6500;
}
.circle-img-blu{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 170px;
  height:170px;
  border-radius: 50%;
  padding:15px;
  margin-bottom: 20px;
  background-color: #56509F;
}

</style>