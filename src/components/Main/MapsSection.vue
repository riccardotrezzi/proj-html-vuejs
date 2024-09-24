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
    <button class="circle-blu">
      <i class="fa-solid fa-location-dot"></i>
    </button>
    <button class="zoom d-flex flex-column">
      <i class="fa-solid fa-plus"></i>
      <i class="fa-solid fa-minus"></i> 
    </button>
  </section>
</template>

<style lang="scss" scoped>

section{
  height: 300px;
  background-image: url("/src/assets/fable-img/images/vt\ \(2\).png");
  background-size: cover;
  position: relative;
}

.circle-blu{
  width: 110px;
  height:110px;
  border-radius: 50%;
  padding:20px;
  margin: auto;
  background-color:#57509f9e;
  border:none;
  color: white;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;

    i{
      font-size: 24px;
    }
}

.zoom{
  background-color: white;
  border: none;
  font-size: 25px;
  text-align: center;
  position: absolute;
  top: 10px;
  right: 10px;

  i{
    padding: 10px;
  }
  i:last-of-type{
    border-top: 1px solid grey;
  }
}
</style>