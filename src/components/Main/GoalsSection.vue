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
    <div class="my-container">
      <div class="row d-flex align-items-center">
        <div class="col-6">
          <div id="text-goals">
            <p>
              We have been educating children for over fifteen years. Our goal is to create a place that engages each child.
            </p>
          </div>

          <div id="subtext-goals">
            <p>
              Praesent arcu gravida vehicula est node maecenas loareet morbi a dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis facilisis venenatis aenean interdum.
            </p>
          </div>

          <div>
            <ul>
              <li class="d-flex align-items-center">
                <img src="/src/assets/fable-img/images/style_1.png" alt="">
                <p>Comprehensive reporting on individual achievement</p>
              </li>
              <li class="d-flex align-items-center">
                <img src="/src/assets/fable-img/images/style_1.png" alt="">
                <p>Educational field trips and school presentations</p>
              </li>
              <li class="d-flex align-items-center">
                <img src="/src/assets/fable-img/images/style_1.png" alt="">
                <p>Individual attention in a small-class setting</p>
              </li>
              <li class="d-flex align-items-center">
                <img src="/src/assets/fable-img/images/style_1.png" alt="">
                <p>Learning program with after-school care</p>
              </li>
              <li class="d-flex align-items-center">
                <img src="/src/assets/fable-img/images/style_1.png" alt="">
                <p>Opportunities to carry out scientific investigations</p>
              </li>
              <li class="d-flex align-items-center">
                <img src="/src/assets/fable-img/images/style_1.png" alt="">
                <p>Positive learning environment for your child</p>
              </li>
              
            </ul>
          </div>

        </div>
        <div class="col-6">
          <div class="row">
            <div class="col-6 d-flex flex-column align-items-center text-center">
              <div class="circle-img-white">
                <img src="/src/assets/fable-img/images/toy.png" alt="">
              </div>
              <h4 class="title-circle">Learning & Fun</h4>
              <p class="text-circle">Praesent modea est gravida node vehicula luctus.</p>
            </div>
            <div class="col-6 d-flex flex-column align-items-center text-center">
              <div class="circle-img-white">
                <img src="/src/assets/fable-img/images/meal.png" alt="">
              </div>
              <h4 class="title-circle">Healthy Meals</h4>
              <p class="text-circle">Terminal interdum a eleifend maecenas est morbi.</p>
            </div>
          </div>
          <div class="row">
            <div class="col-6 d-flex flex-column align-items-center text-center">
              <div class="circle-img-white">
                <img src="/src/assets/fable-img/images/school.png" alt="">
              </div>
              <h4 class="title-circle">Friendly Place</h4>
              <p class="text-circle">Terminal interdum a eleifend maecenas est morbi.</p>
            </div>
            <div class="col-6 d-flex flex-column align-items-center text-center">
              <div class="circle-img-white">
                <img src="/src/assets/fable-img/images/shield.png" alt="">
              </div>
              <h4 class="title-circle">Children Safety</h4>
              <p class="text-circle">Praesent modea est gravida node vehicula luctus.</p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<style lang="scss" scoped>

section{
  background-color: #F5F5F5;
  padding: 20px 0;
}

#text-goals{
  font-size: 25px;
  color:#5E58A4;
  line-height: 30px;
  margin-bottom: 35px;
}
#subtext-goals{
  color:grey;
  margin-bottom: 25px;
}

ul{
  list-style: none;
  padding: 0;

  li{
    line-height: 10px;
    margin: 10px 0;
  }
  img{
    height: 18px;
    margin-right: 10px;
  }
  p{
    font-size: 16px;
    margin:0;
    color: grey;
  }
}

.circle-img-white{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 70px;
  height:70px;
  border-radius: 50%;
  padding:20px;
  margin: 20px 0;
  background-color: white;

}
.title-circle{
  color: #56509F; 
  margin-bottom: 20px;
}

.text-circle{
  font-size: 17px;
  font-weight: 300;
  color: grey;
  margin-bottom: 15px;
}
</style>