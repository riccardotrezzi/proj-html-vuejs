<script>
import WelcomeSection from './Main/WelcomeSection.vue';
import ClassesSection from './Main/ClassesSection.vue';
import StaffSection from './Main/StaffSection.vue';

export default {
  data() {
    return {
    };
  },
  components:{
    WelcomeSection,
    ClassesSection,
    StaffSection
  }

}
</script>

<template>
    <main>
        <WelcomeSection />
        <ClassesSection />
        <StaffSection />
    </main>
</template>

<style scoped>

</style>