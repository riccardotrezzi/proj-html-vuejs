<script>
import GoalsSection from './GoalsSection.vue';


export default {
  data() {
    return {
    };
  },
  components:{
    GoalsSection
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

    <div class="my-container">
      <div class="row w-100 d-flex justify-content-between">
        <div id="text-sx" class="col-6">
          <p>
            We provided four classes with nine to twenty children each aged twelve month to five years of age.
          </p>
        </div>
        <div id="text-dx" class="col-6">
          <p>
            Praesent arcu gravida vehicula est node maecenas loareet morbi a dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis facilisis venenatis. Aenean interdum, nibh vitae sodales, magna ante feugiat elit maecenas.
          </p>
        </div>
      </div>
    </div>

    <div class="my-container my-4">
      <div class="row w-100 d-flex justify-content-between flex-nowrap">
        <div class="card col-6">
          <div class="row">
            <div class="card-sx p-3 col-6 g-0">
              <div class="title-card">
                <h3>Little Lambs</h3>
                <h6>Class name</h6>
              </div>
              <div class="row">
                <div class="age-card col-6 d-flex flex-column justify-content-center align-items-center text-center">
                  <h4>12-24</h4>
                  <h6>Month olds</h6>
                </div>
                <div class="class-card col-6 text-center">
                  <h4>9</h4>
                  <h6>Class size</h6>
                </div>
              </div>
            </div>
            <div class="card-dx col-6 g-0">
              <img src="/src/assets/fable-img/images/class_01-690x506.jpg" alt="Class-1">
              <button class="button-card">
                Read more
                <i class="fa-solid fa-chevron-right"></i>
              </button>
            </div>    
          </div>
        </div>
        <div class="card col-6">
          <div class="row">
            <div class="card-sx p-3 col-6 g-0">
              <div class="title-card">
                <h3>Bouncy Bears</h3>
                <h6>Class name</h6>
              </div>
              <div class="row">
                <div class="age-card col-6 d-flex flex-column justify-content-center align-items-center text-center">
                  <h4>2-3</h4>
                  <h6>Years olds</h6>
                </div>
                <div class="class-card col-6 text-center">
                  <h4>12</h4>
                  <h6>Class size</h6>
                </div>
              </div>
            </div>
            <div class="card-dx col-6 g-0">
              <img src="/src/assets/fable-img/images/class_02-690x506.jpg" alt="Class-1">
              <button class="button-card">
                Read more
                <i class="fa-solid fa-chevron-right"></i>
              </button>
            </div>    
          </div>
        </div>
      </div>
      <div class="row w-100 d-flex justify-content-between flex-nowrap">
        <div class="card col-6">
          <div class="row">
            <div class="card-sx p-3 col-6 g-0">
              <div class="title-card">
                <h3>Tenderhearts</h3>
                <h6>Class name</h6>
              </div>
              <div class="row d-flex ">
                <div class="age-card col-6 d-flex flex-column justify-content-center text-center">
                  <h4>3-4</h4>
                  <h6>Years olds</h6>
                </div>
                <div class="class-card col-6 text-center">
                  <h4>15</h4>
                  <h6>Class size</h6>
                </div>
              </div>
            </div>
            <div class="card-dx col-6 g-0">
              <img src="/src/assets/fable-img/images/class_03-690x506.jpg" alt="Class-1">
              <button class="button-card">
                Read more
                <i class="fa-solid fa-chevron-right"></i>
              </button>
            </div>    
          </div>
        </div>
        <div class="card col-6">
          <div class="row">
            <div class="card-sx p-3 col-6 g-0">
              <div class="title-card">
                <h3>Shining Stars</h3>
                <h6>Class name</h6>
              </div>
              <div class="row">
                <div class="age-card col-6 d-flex flex-column justify-content-center align-items-center text-center">
                  <h4>4-5</h4>
                  <h6>Years olds</h6>
                </div>
                <div class="class-card col-6 text-center">
                  <h4>20</h4>
                  <h6>Class size</h6>
                </div>
              </div>
            </div>
            <div class="card-dx col-6 g-0">
              <img src="/src/assets/fable-img/images/class_04-690x506.jpg" alt="Class-1">
              <button class="button-card">
                Read more
                <i class="fa-solid fa-chevron-right"></i>
              </button>
            </div>    
          </div>
        </div>
      </div>
    </div>
  </section>
  <GoalsSection />
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

#text-sx {
  color: #5E58A4;
  font-size: 30px;
  line-height: 35px;
  margin-bottom: 25px;
}

#text-dx{
  font-size: 16px;
  color: grey;
}

.card{
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 15px;
}

.card-sx{
  background-color: #5E58A4;

}

.title-card{
  color: white;
  margin-bottom: 22px;

    h6{
      color: lightgrey;
    }
}

.age-card{
  color: white;
  line-height: 10px;
  border-right: 0.5px solid rgb(193, 193, 193);

    h4{
      font-size: 18px;
    }
    h6{
      font-size: 14px;

    }
}

.class-card{
  color: white;
  line-height: 10px;
    h4{
      font-size: 18px;
    }
    h6{
      font-size: 14px;

    } 
}

.card-dx{
  position: relative;
}

.button-card{
  text-transform: uppercase;
  padding: 12px;
  border: none;
  color: white;
  background-color: #fe6500;
  position: absolute;
  bottom: 0;
  right: 0;
}
.button-card:hover{
  background-color: #5E58A4;
}
</style>