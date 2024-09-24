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
  <section>
    <div class="my-container">
      <div id="title-contact" class="d-flex flex-column align-items-center">
        <h1 class="open-sans-light">Contact Us</h1>
        <p>Our postal address and contact details</p>
        <img class="m-3" src="/src/assets/fable-img/images/header_divider.png" alt="">
      </div>

      <div class="row">
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="icon">
              <img src="/src/assets/fable-img/images/envelope (1).png" alt="">
            </div>
            <h4 class="title-icon">Postal Address</h4>

            <p class="text-icon">Fable Care Center</p>
            <p class="text-icon">85 Fentiman Ave</p>
            <p class="text-icon">Ottawa, ON K1S 0T7</p>
          </div>
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="icon">
              <img src="/src/assets/fable-img/images/mobile.png" alt="">
            </div>
            <h4 class="title-icon">Phone & E-mail</h4>

            <p class="text-icon">Phone: 1-800-64-38</p>
            <p class="text-icon">Fax: 1-800-64-39</p>
            <p class="text-icon">office@fable.com</p>
          </div>
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="icon">
              <img src="/src/assets/fable-img/images/clock.png" alt="">
            </div>
            <h4 class="title-icon">Business Hours</h4>
            
            <p class="text-icon">Monday/Friday</p>
            <p class="text-icon">8.00 am / 5.00 pm</p>
            <p class="text-icon">Weekend Closed</p>
          </div>
          <div class="col-3 d-flex flex-column align-items-center text-center">
            <div class="icon">
              <img src="/src/assets/fable-img/images/document (1).png" alt="">
            </div>
            <h4 class="title-icon">Session</h4>
            
            <p class="text-icon">Mornings, 8 am / 12 noon</p>
            <p class="text-icon">Afternoons, 1 pm / 5 pm</p>
            <p class="text-icon">Full Day, 8 am / 5 pm</p>
          </div>
        </div>
        <div class="row my-5">
          <div class="col-6 d-flex flex-column">
            <input class="input-contact" type="text" placeholder="Your Name">
            <input class="input-contact" type="text" placeholder="Your Email">
            <input class="input-contact" type="text" placeholder="Subject">
          </div>
          <div class="col-6">
            <input class="textarea-contact" type="text" placeholder="Your Message">
          </div>
        </div>

        <div class="d-flex justify-content-center">
        <button class="blog-button">
          <span>send message</span>
        </button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
#title-contact{
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

.icon{
  margin: 30px;
    img{
      width: 50px;
    }
}

.title-icon{
  color: #56509F; 
  margin-bottom: 20px;
}

.text-icon{
  font-size: 18px;
  font-weight: 300;
  color: grey;
  line-height: 12px;
}

.input-contact{
  padding: 10px;
  margin: 5px 0;
}

.textarea-contact{
  width: 100%;
  height: 100%;
  padding: 10px;

}

.blog-button{
  text-transform: uppercase;
  padding: 12px;
  border: none;
  color: white;
  background-color: #fe6500;
  margin: 5px 0;
}
.blog-button:hover{
  background-color: #5E58A4;
}
</style>