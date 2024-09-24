<script>

export default {
  data() {
    return {
      reviews: [
        {
          id: 1,
          text: 'Fable Kindergarten is a great place for my daughter to start her schooling experience. It’s welcoming and safe and my daughter loves being there.',
          author: 'Matthew D. Campbell'
        },
        {
          id: 2,
          text: 'I have a 1 year old and a 5 year old who have been attending for a year now. I can not tell you how much I adore and appreciate all of the wonderful staff.',
          author: 'Kennet M. Garcia'
        },
        {
          id: 3,
          text: 'I have to say that I have 2 children ages 5 and 2 and have used various daycare’s in Kindergartens and this is by far the very best I have ever used.',
          author: 'Cecil J. Kirk'
        },
        {
          id: 4,
          text: 'I have a 1 year old and a 5 year old who have been attending for a year now. I can not tell you how much I adore and appreciate all of the wonderful staff.',
          author: 'Joe R. Hamblen'
        },
        {
          id: 5,
          text: 'This letter is to recognize you and your staff for doing an excellent job teaching my son. His skill level is significantly better since attending Fable.',
          author: 'Tony I. Robinette'
        },
        {
          id: 6,
          text: 'I have a 1 year old and a 5 year old who have been attending for a year now. I can not tell you how much I adore and appreciate all of the wonderful staff.',
          author: 'Emma E. Shook'
        }
      ],
      currentSlide: 0
    };
  },
  methods: {
    goToSlide(index) {
        this.currentSlide = index;
    }
  }

}
</script>

<template>
  <section class="d-flex align-items-center">
    <div class="my-container">
      <div class="row text-jumbo">
        <div class="col-12 d-flex flex-column align-items-center text-center">
          <div class="circle-icon">
            <img src="/src/assets/fable-img/images/quote_alt.png" alt="">
          </div>
          <div v-for="(review, index) in reviews" :key="review.id" class="review" :class="{ active: index === currentSlide}" >
            <p class="title-data open-sans-light">{{ review.text }}</p>
            <hr>
            <h6 class="text-data">{{review.author}}</h6>
          </div>
          
        </div>
      </div>
      <div class="row d-flex flex-row justify-content-center rect-data-slider" >
        <div class="col-2 g-0" v-for="(review, index) in reviews" :key="review.id" :class="{ active: index === currentSlide}" @click="goToSlide(index)">
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

.text-jumbo {
  overflow: hidden;
}

.review {
  width: 100%;
  display: none; /* Nascondiamo le slide per impostazione predefinita */
  color: #fff;
  padding: 10px;
}

.slide.active {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center; /* Visualizziamo solo la slide attiva */
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

.active-button{
  position: relative;
    bottom: 10px;
    left: 50%; 
    transform: translate(-50%,-50%);
}
</style>