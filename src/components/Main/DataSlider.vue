<script>

export default {
  data() {
    return {
    };
  }

}
</script>

<template>
  <section class="d-flex align-items-center">
    <div class="my-container">
      <div class="row">
        <div class="col-3 d-flex flex-column align-items-center text-center">
          <div class="circle-icon">
            <h4>507</h4>
          </div>
          <h4 class="title-data open-sans-light">Our Pupils</h4>
          <p class="text-data">Pulvinar forte maestro nodew terminal est ellipsis prism.</p>
        </div>
        <div class="col-3 d-flex flex-column align-items-center text-center">
          <div class="circle-icon">
            <h4>507</h4>
          </div>
          <h4 class="title-data open-sans-light">Our Pupils</h4>
          <p class="text-data">Pulvinar forte maestro nodew terminal est ellipsis prism.</p>
        </div>
        <div class="col-3 d-flex flex-column align-items-center text-center">
          <div class="circle-icon">
            <h4>507</h4>
          </div>
          <h4 class="title-data open-sans-light">Our Pupils</h4>
          <p class="text-data">Pulvinar forte maestro nodew terminal est ellipsis prism.</p>
        </div>
        <div class="col-3 d-flex flex-column align-items-center text-center">
          <div class="circle-icon">
            <h4>507</h4>
          </div>
          <h4 class="title-data open-sans-light">Our Pupils</h4>
          <p class="text-data">Pulvinar forte maestro nodew terminal est ellipsis prism.</p>
        </div>
      </div>
      <div class="row rect-data-slider">
        <button class="rect-data"></button>
        <button class="rect-data"></button>
        <button class="rect-data"></button>
        <button class="rect-data"></button>
        <button class="rect-data"></button>
        <button class="rect-data"></button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

section{
  height: 450px;
  background-image: url("/src/assets/fable-img/images/parallax_01.jpg");
  background-attachment: fixed;
  position:relative;
}

.circle-icon{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 170px;
  height:170px;
  border-radius: 50%;
  padding:15px;
  margin-bottom: 20px;
  background-color: #fe660000;
  border: 2px solid white;

    h4{
      font-size:50px;
      font-weight: 300;
      color: white;
    }
}

.title-data {
  font-size: 32px;
  color:white;
}

.open-sans-light {
  font-family: "Open Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

.text-data{
  color:white;
}

/*Bottoncini */

.rect-data-slider{
    position: absolute;
    bottom: 0;
    left: 50%; 
    transform: translate(-50%,-50%);

    .rect-data{
        background-color: rgba(255, 255, 255, 0);
        border: 2px solid white;
        width: 50px;
        height: 15px;
        margin: 5px;
    }
}
</style>