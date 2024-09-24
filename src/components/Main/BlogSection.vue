<script>
import MapsSection from './MapsSection.vue';


export default {
  data() {
    return {
    };
  },
  components:{
    MapsSection
  }

}
</script>

<template>
  <section>
    <div class="my-container">
      <div id="title-blog" class="d-flex flex-column align-items-center">
        <h1 class="open-sans-light">What's New</h1>
        <p>Keep up to date with the latest news</p>
        <img class="m-3" src="/src/assets/fable-img/images/header_divider.png" alt="">
      </div>

      <div class="row">
        <div class="col-4">
          <h6 class="blog-data">October 03, 2014</h6>
          <img src="/src/assets/fable-img/images/blog_09.jpg" alt="Blog_Img-1">
          <div>
            <h4 class="title-article open-sans-title">Drawing and Painting Lessons</h4>
            <p class="text-article">Magna est consectetur interdum modest dictum. Curabitur est faucibus, malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum</p>
          </div>

          <hr>

          <div class="d-flex">
            <div class="blog-details">
              <img src="/src/assets/fable-img/images/author.png" alt="">
              <h6>Anna Brown</h6>
            </div>
            <div class="blog-details">
              <img src="/src/assets/fable-img/images/category.png" alt="">
              <h6>Events, Fun</h6>
            </div>

          </div>
        </div>
        <div class="col-4">
          <h6 class="blog-data">October 03, 2014</h6>
          <img src="/src/assets/fable-img/images/blog_10.jpg" alt="Blog_Img-2">
          <div>
            <h4 class="title-article open-sans-title">Fall Parents Meeting Day</h4>
            <p class="text-article">Magna est consectetur interdum modest dictum. Curabitur est faucibus, malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum</p>
          </div>

          <hr>

          <div class="d-flex">
            <div class="blog-details">
              <img src="/src/assets/fable-img/images/author.png" alt="">
              <h6>Anna Brown</h6>
            </div>
            <div class="blog-details">
              <img src="/src/assets/fable-img/images/category.png" alt="">
              <h6>Events, Fun</h6>
            </div>

          </div>
        </div>
        <div class="col-4">
          <h6 class="blog-data">October 03, 2014</h6>
          <img src="/src/assets/fable-img/images/blog_08.jpg" alt="Blog_Img-3">
          <div>
            <h4 class="title-article open-sans-title">Birthday in Kindergarten</h4>
            <p class="text-article">Magna est consectetur interdum modest dictum. Curabitur est faucibus, malesuada esttincidunt etos et mauris, nunc a libero govum est cuprum</p>
          </div>

          <hr>

          <div class="d-flex">
            <div class="blog-details">
              <img src="/src/assets/fable-img/images/author.png" alt="">
              <h6>Anna Brown</h6>
            </div>
            <div class="blog-details">
              <img src="/src/assets/fable-img/images/category.png" alt="">
              <h6>Events, Fun</h6>
            </div>

          </div>
        </div>
        
      </div>
      <div class="d-flex justify-content-center">
        <button class="blog-button">
          <span>go to blog </span>
          <i class="fa-solid fa-chevron-right"></i>
        </button>
      </div>
      
    </div>
  </section>
  <MapsSection />
</template>

<style lang="scss" scoped>

#title-blog{
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

.title-article{
  color: #56509F; 
  margin: 15px 0;
}

.text-article{
  font-size: 16px;
  font-weight: 300;
  color: grey;
  margin-bottom: 15px;
}

.blog-data{
  font-size: 17px;
  font-weight: 300;
  color: grey;
  margin-right: 10px;
  margin-bottom: 15px;
}

.blog-details{
  display: flex;
  margin-right: 10px;

  img {
    height: 20px;
    margin-right: 15px;
  }

  h6{
    font-size: 17px;
    font-weight: 300;
    color: grey;
    margin-right: 10px;
    margin-bottom: 15px;
  }
}

.blog-button{
  text-transform: uppercase;
  padding: 12px;
  border: none;
  color: white;
  background-color: #fe6500;
  margin: 25px 0;
}
.blog-button:hover{
  background-color: #5E58A4;
}
</style>