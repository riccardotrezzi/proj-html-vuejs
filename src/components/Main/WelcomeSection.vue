<script>
export default {
  data() {
    return {
    };
  }

}
</script>

<template>
    <section class="m-5">
      <div class="my-container">
        <div id="title-section" class="d-flex flex-column align-items-center">
          <h1 class="open-sans-light">Welcome to Fable</h1>
          <p>Fable daycare, preschool, and kindergarten</p>
          <img class="m-3" src="/src/assets/fable-img/images/header_divider.png" alt="">
        </div>
        
        <div class="row">
          <div class="col-3">
            <div class="circle-img">
              <img src="/src/assets/fable-img/images/schoolbag_alt.png" alt="">
            </div>
            <h4>Morbi Etos</h4>
            <p>Praesent interdum est gravida vehicula est node maecenas loareet morbi a dosis luctus novum est praesent.</p>
          </div>
          <div class="col-3">
            <div class="circle-img">
              <img src="/src/assets/fable-img/images/schoolbag_alt.png" alt="">
            </div>
            <h4>Morbi Etos</h4>
            <p>Praesent interdum est gravida vehicula est node maecenas loareet morbi a dosis luctus novum est praesent.</p>
          </div>
          <div class="col-3">
            <div class="circle-img">
              <img src="/src/assets/fable-img/images/globe_alt.png" alt="">
            </div>
            <h4>Morbi Etos</h4>
            <p>Praesent interdum est gravida vehicula est node maecenas loareet morbi a dosis luctus novum est praesent.</p>
          </div>
          <div class="col-3">
            <div class="circle-img">
              <img src="/src/assets/fable-img/images/schoolbag_alt.png" alt="">
            </div>
            <h4>Morbi Etos</h4>
            <p>Praesent interdum est gravida vehicula est node maecenas loareet morbi a dosis luctus novum est praesent.</p>
          </div>
        </div>
      </div>
    </section>
</template>

<style lang="scss" scoped>

#title-section{
  margin: 20px 0;

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