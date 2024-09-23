<script>
import WelcomeSection from './Main/Welcome/WelcomeSection.vue';
import ClassesSection from './Main/OurClasses/ClassesSection.vue';

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