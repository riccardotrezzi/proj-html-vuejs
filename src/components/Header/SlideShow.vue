<script>
const basePath = '../src/assets/fable-img/jumbotron/';

export default {
  data() {
    return {
        slides: [
            {
                id: 1,
                title: 'Welcome to Fable',
                subtitle: 'Perfect Education',
                text: 'For Your Child',
                image: `${basePath}Jumbotron-1.png`,
                alignCenter: 'textcent',
            },
            {
                id: 2,
                title: 'Friendly Atmosphere',
                subtitle: 'Welcoming Place',
                text: 'For Every Child',
                image: `${basePath}Jumbotron-2.png`,
                alignSx: 'textsx',
            },
            {
                id: 3,
                title: 'Learning & Fun',
                subtitle: 'Learning Programs',
                text: '& After School Care',
                image: `${basePath}Jumbotron-3.png`,
                alignSx: 'textsx',
            }
        ],
        currentSlide: 0
    };
  },
    mounted() {
        setInterval(this.nextSlide, 7000); // Cambia diapositiva ogni 5 secondi
    },
    methods: {
        nextSlide() {
            if(this.currentSlide + 1 < this.slides.length) {
                this.currentSlide++;
            }
            else {
                this.currentSlide = 0;
            }
        },
        prevSlide () {
            if (this.currentSlide > 0) {
                this.currentSlide--;
            }
            else {
                this.currentSlide = this.slides.length - 1;
            }
        },
        goToSlide(index) {
            this.currentSlide = index;
        }
    }

}
</script>

<template>
    <section>
        <div class="jumbotron">
            <div class="slideshow">
                <div v-for="(slide, index) in slides" :key="slide.id" class="slide" :class="{ active: index === currentSlide}" :style="{ backgroundImage: 'url(' + slide.image + ')' }" >
                    
                    <div class="d-flex w-100 align-items-center justify-content-between px-3">
                        <button class="arrow-button d-flex align-items-center justify-content-center" @click="prevSlide">
                            <i class="fa-solid fa-chevron-left"></i>
                        </button>
                        <button class="arrow-button d-flex align-items-center justify-content-center" @click="nextSlide">
                            <i class="fa-solid fa-chevron-right"></i>
                        </button>
                    </div>

                    <div class="my-container" :class="{textsx: slide.alignSx, textcent: slide.alignCenter}">
                        <h2 class="coming-soon-regular">{{ slide.title }}</h2>
                        <p class="open-sans-bold">{{ slide.subtitle }}</p>
                        <p class="open-sans-light">{{ slide.text }}</p>

                        <button class="button-jumbotron">
                            <a class="link-jumbotron" href="#">Buy this theme now</a>
                        </button>
                    </div>
                    
                </div>

                <div class="rect-slide">
                    <span v-for="(slide, index) in slides" :key="slide.id" :class="{ active: index === currentSlide }" @click="goToSlide(index)">
                        
                        <button class="rect"></button>
                    </span>
                </div>
                
            </div>
        </div>
    </section>


    
</template>

<style lang="scss" scoped>
.jumbotron {
    position: relative;
    overflow: hidden;
}
  
.slideshow {
display: flex;
}

.slide {
width: 100%;
height: 600px;
background-size: cover;
display: none; /* Nascondiamo le slide per impostazione predefinita */
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
color: #fff;
padding: 10px;
}

.slide.active {
display: flex; /* Visualizziamo solo la slide attiva */
}

.textcent{
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.textsx{
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: flex-start;
    text-align:start;
}

.my-container > h2{
margin-bottom: 15px;
font-size: 30px;
color:#FE6500;
}

.coming-soon-regular {
font-family: "Coming Soon", cursive;
font-weight: 400;
font-style: normal;
}

.my-container > p:first-of-type{
line-height: 35px;
font-size: 50px;
font-weight: bold;
color:#5E58A4;
}

.open-sans-bold {
font-family: "Open Sans", sans-serif;
font-optical-sizing: auto;
font-weight: bold;
font-style: normal;
}

.my-container > p:last-of-type{
line-height: 45px;
font-size: 50px;
font-weight: 300;
color:#5E58A4;
} 

.open-sans-light {
font-family: "Open Sans", sans-serif;
font-optical-sizing: auto;
font-weight: 300;
font-style: normal;
}

.button-jumbotron {
width: fit-content;
margin-top: 10px;
padding: 15px;
border: none;
background-color: #FE6500;

    a{
        text-decoration: none;
        color:white;
        font-size: 16px;
        font-weight: bold;
        text-transform: uppercase;
    }
}

/*Bottoncini */

.arrow-button{
    width: 45px;
    height: 45px;
    padding: 10px;
    border: none;
    border-radius: 50%;
    background-color: white;
}

.arrow-button:hover{
    width: 45px;
    height: 45px;
    padding: 10px;
    border: none;
    border-radius: 50%;
    color: white;
    background-color:#5E58A4;
}
.rect-slide{
    position: absolute;
    bottom: 0;
    left: 50%; 
    transform: translate(-50%,-50%);

    .rect{
        background-color: rgba(255, 255, 255, 0);
        border: 2px solid #FE6500;
        width: 50px;
        height: 20px;
        margin: 5px;
    }
}



</style>