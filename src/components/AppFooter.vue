<script>
export default {
  data() {
    return {
    };
  }

}
</script>

<template>
  <footer>
    <section>
      <div class="my-container">
        <div class="row">
          <div class="col-3 py-5 px-3">
            <div>
              <h4 class="title-col-footer">About Us</h4>
              <hr>
            </div>
            <div>
              <p class="text-section-footer">
                Elipsis magna a nulla elite forte maecenas est elementum magna etos interdum movum morbi vehicula morbi.
              </p>
              <img src="/src/assets/fable-img/images/logo_footer.png" alt="">
            </div>
          </div>
          <div class="col-3 py-5 px-3">
            <div>
              <h4 class="title-col-footer">Archives</h4>
              <hr>
            </div>
            <div class="d-flex flex-column">
              <button class="button-archives d-flex align-items-center text-start">
                october 2014 (2)
              </button>
              <button class="button-archives d-flex align-items-center text-start">
                september 2014 (2)
              </button>
              <button class="button-archives d-flex align-items-center text-start">
                august 2014 (2)
              </button>
              <button class="button-archives d-flex align-items-center text-start">
                july 2014 (2)
              </button>
              <button class="button-archives d-flex align-items-center text-start">
                june 2014 (2)
              </button>
              <button class="button-archives d-flex align-items-center text-start">
                may 2014 (2)
              </button>
            </div>
          </div>
          <div class="col-3 py-5 px-3">
            <div>
              <h4 class="title-col-footer">our features</h4>
              <hr>
            </div>
            <div>
              <p class="text-section-footer">
                Nunc gravida rutrum mauris vehin hasellus ac pretium augue vivamul lacus ligul mattis ac vene:
              </p>
              <ul>
                <li class="d-flex align-items-center">
                  <img src="/src/assets/fable-img/images/style_4_alt.png" alt="">
                  <p>Friendly and welcoming place</p>
                </li>
                <li class="d-flex align-items-center">
                  <img src="/src/assets/fable-img/images/style_4_alt.png" alt="">
                  <p>Science and art classes</p>
                </li>
                <li class="d-flex align-items-center">
                  <img src="/src/assets/fable-img/images/style_4_alt.png" alt="">
                  <p>Positive learning environment</p>
                </li>
                <li class="d-flex align-items-center">
                  <img src="/src/assets/fable-img/images/style_4_alt.png" alt="">
                  <p>Educational field trips</p>
                </li>
                <li class="d-flex align-items-center">
                  <img src="/src/assets/fable-img/images/style_4_alt.png" alt="">
                  <p>Writing and reading classes</p>
                </li>
                <li class="d-flex align-items-center">
                  <img src="/src/assets/fable-img/images/style_4_alt.png" alt="">
                  <p>Science and art classes</p>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-3 py-5 px-3">
            <div>
              <h4 class="title-col-footer">recent posts</h4>
              <hr>
            </div>
            <div class="row w-100 d-flex gx-0 my-3">
              <div id="img-blog-first" class="col-4 g-0">
                
              </div>
              <div class="col-8 g-0">
                <h4 class="link-blog">
                  <a href="#">
                    Drawing and Painting Lessons
                  </a>
                </h4>
                <div class=" d-flex">
                  <img class="calendar-footer-blog" src="/src/assets/fable-img/images/date_footer.png" alt="">
                  <h6 class="blog-data">October 03, 2014</h6>
                </div>
              </div>
            </div>
            <div class="row w-100 d-flex gx-0 my-3">
              <div id="img-blog-second" class="col-4 g-0">
                
              </div>
              <div class="col-8 g-0">
                <h4 class="link-blog">
                  <a href="#">
                    Fall Parents Meeting Day
                  </a>
                </h4>
                <div class=" d-flex">
                  <img class="calendar-footer-blog" src="/src/assets/fable-img/images/date_footer.png" alt="">
                  <h6 class="blog-data">October 03, 2014</h6>
                </div>
              </div>
            </div>
            <div class="row w-100 d-flex gx-0 my-3">
              <div id="img-blog-third" class="col-4 g-0">
                
              </div>
              <div class="col-8 g-0">
                <h4 class="link-blog">
                  <a href="#">
                    Birthday in Kindergarten
                  </a>
                </h4>
                <div class=" d-flex">
                  <img class="calendar-footer-blog" src="/src/assets/fable-img/images/date_footer.png" alt="">
                  <h6 class="blog-data">October 03, 2014</h6>
                </div>
              </div>
            </div>
            
          </div>
        </div>
      </div>
    </section>

    <!--Social & Copyright-->
    <div>
      <div class="d-flex justify-content-center">
        <button class="social-footer">
          <img src="/src/assets/fable-img/images/mail.png" alt="">
        </button>
        <button class="social-footer">
          <img src="/src/assets/fable-img/images/facebook.png" alt="">
        </button>
        <button class="social-footer">
          <img src="/src/assets/fable-img/images/pinterest.png" alt="">
        </button>
        <button class="social-footer">
          <img src="/src/assets/fable-img/images/facebook.png" alt="">
        </button>
        <button class="social-footer">
          <img src="/src/assets/fable-img/images/pinterest.png" alt="">
        </button>
       
      </div>
      <div class="d-flex justify-content-center copyright">
        <p>© Fable - Children Kindergarten Vite + Vue by Riccardo Trezzi</p>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>

footer{
  padding: 25px 0;
}
section{
  width: 100%;
  height: 500px;
  background-image: url("/src/assets/fable-img/images/pattern.png");
  background-size: cover;
}

.title-col-footer{
  text-transform: uppercase;
  font-weight: 300;
  font-size: 22px;
  color: white;
  line-height: 18px;
}

hr{
  width: 30%;
  border: 1px solid #AFAAD0;
}

.text-section-footer{
  font-size: 15px;
  font-weight: 300;
  color: #AFAAD0;
  margin: 15px 0;
}

.button-archives{
  width: 100%;
  height: 40px;
  padding: 10px;
  border: 2px solid #AFAAD0;
  background-color: rgba(255, 255, 255, 0);
  color: #AFAAD0;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.button-archives:hover{
  border: 2px solid white;
  color: white;
}

ul{
  list-style: none;
  padding: 0;

  li{
    line-height: 15px;
    margin: 10px 0;
  }
  img{
    height: 18px;
    margin-right: 10px;
  }
  p{
    font-size: 14px;
    margin:0;
    color: #AFAAD0;
  }
}


#img-blog-first{
  width: 70px;
  height: 70px;
  background-image: url("/src/assets/fable-img/images/gallery_03.jpg");
  background-size: cover;
  margin-right: 10px;
}

#img-blog-second{
  width: 70px;
  height: 70px;
  background-image: url("/src/assets/fable-img/images/gallery_04.jpg");
  background-size: cover;
  margin-right: 10px;
}
#img-blog-third{
  width: 70px;
  height: 70px;
  background-image: url("/src/assets/fable-img/images/gallery_02.jpg");
  background-size: cover;
  margin-right: 10px;
}

.link-blog{
  font-size: 16px;
  
    a{
      text-decoration: none;
      color: white;
    }
    a:hover{
      text-decoration: underline;
    }
}

.calendar-blog-footer{
  margin-right: 5px;
}

.blog-data{
  font-size: 14px;
  font-weight: 300;
  color: #AFAAD0;
  margin-left: 10px;
}

.social-footer{
  width: 50px;
  height: 50px;
  background-color: #FE6500;
  margin-right: 8px;
  margin-top: 30px;
  border: none;
}
.social-footer:hover{
  background-color: #56509F;
}

.copyright{
  font-size: 15px;
  font-weight: 300;
  color: grey;
  margin: 15px 0;
}
</style>