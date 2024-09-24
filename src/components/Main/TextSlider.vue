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
        <div class="col-12 d-flex flex-column align-items-center text-center">
          <div class="circle-icon">
            <img src="/src/assets/fable-img/images/quote_alt.png" alt="">
          </div>
          <p class="title-data open-sans-light">
            I have a 1 year old and a 5 year old who have been attending for a year now. I can not tell you how much I adore and appreciate all of the wonderful staff.
          </p>
          <hr>
          <h6 class="text-data">Matthew D. Campbell</h6>
        </div>
      </div>
      <div class="row d-flex flex-row justify-content-center rect-data-slider">
        <div class="col-2 g-0">
          <button class="rect-data active"></button>
        </div>
        <div class="col-2 g-0">
          <button class="rect-data"></button>
        </div>
        <div class="col-2 g-0">
          <button class="rect-data"></button>
        </div>
        <div class="col-2 g-0">
          <button class="rect-data"></button>
        </div>
        <div class="col-2 g-0">
          <button class="rect-data"></button>
        </div>
        <div class="col-2 g-0">
          <button class="rect-data"></button>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

section{
  height: 500px;
  background-image: url("/src/assets/fable-img/images/parallax_02.jpg");
  background-attachment: fixed;
  position:relative;
}

.circle-icon{
  display: flex;
  justify-content: center;
  align-items: center;
  width:100px;
  height:100px;
  border-radius: 50%;
  padding:15px;
  margin-bottom: 20px;
  background-color: #fe660000;
  border: 2px solid white;
}

.title-data {
  font-size: 35px;
  color:white;
}

hr{
  width: 10%;
  border: 1px solid white;
}
.open-sans-light {
  font-family: "Open Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: 300;
  font-style: normal;
}

.text-data{
  color:white;
  margin-bottom: 35px;
}

/*Bottoncini */

.rect-data-slider{
    position: absolute;
    bottom: 5px;
    left: 50%; 
    transform: translate(-50%,-50%);
    margin-bottom: 10px;

    .rect-data{
        background-color: rgba(255, 255, 255, 0);
        border: 2px solid white;
        width: 50px;
        height: 15px;
        margin:0 5px;
    }
    .rect-data:hover{
        background-color: rgba(255, 255, 255, 0);
        border: 2px solid lightgrey;
    }

}

.active{
  position: relative;
    bottom: 10px;
    left: 50%; 
    transform: translate(-50%,-50%);
}
</style>