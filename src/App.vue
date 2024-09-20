<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  data() {
    return { 
      message: ''
    }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <AppHeader />

  <AppMain />

  <AppFooter />
</template>

<style lang="scss">
@use 'assets/scss/main.scss' as *;
@import 'bootstrap/scss/bootstrap';
</style>
