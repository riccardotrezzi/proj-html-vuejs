<script>

export default {
  data() {
    return {
    };
  },
  components:{
    
  }

}
</script>

<template>
  <!--OUR CLASSES-->
  <section>
    <div class="my-container">
      <div id="title-classes" class="d-flex flex-column align-items-center">
          <h1 class="open-sans-light">Our Classes</h1>
          <p>Our preschool program has four dedicated classes</p>
          <img class="m-3" src="/src/assets/fable-img/images/header_divider.png" alt="">
        </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
#title-classes{
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
</style>