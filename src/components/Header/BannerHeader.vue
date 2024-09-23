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
        <div class="my-container d-flex align-items-center">
            <h2>
                How to Enroll Your Child to a Class?
            </h2>

            <button>
                <span>learn more</span>
                <i class="fa-solid fa-chevron-right"></i>
            </button>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section{
    height: 130px;
    background-image: url("/src/assets/fable-img/images/pattern.png");
    background-attachment: fixed;
}

h2{
    font-weight: 300;
    color: white;
    margin-right: 20px;
}

button{
    width: 170px;
    height: 60px;
    padding: 10px;
    border: 2px solid white;
    background-color: rgba(255, 255, 255, 0);

    span {
        margin-right: 10px;
        text-transform: uppercase;
        color: white;
    }

    i{
        color: white; 
    }

}

button:hover{
    width: 170px;
    padding: 10px;
    border: 2px solid white;
    background-color: #ffffff;

    span {
        margin-right: 10px;
        text-transform: uppercase;
        color: black;
    }

    i{
        color: black; 
    }

}
</style>