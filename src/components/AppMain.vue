<script>
import WelcomeSection from './Main/WelcomeSection.vue';
import ClassesSection from './Main/ClassesSection.vue';

export default {
  data() {
    return {
    };
  },
  components:{
    WelcomeSection,
    ClassesSection
  }

}
</script>

<template>
    <main>
        <WelcomeSection />
        <ClassesSection />
    </main>
</template>

<style scoped>

</style>