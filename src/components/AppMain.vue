<script>
import WelcomeSection from './Main/WelcomeSection.vue';
import ClassesSection from './Main/ClassesSection.vue';
import StaffSection from './Main/StaffSection.vue';
import BlogSection from './Main/BlogSection.vue';
import ContactSection from './Main/ContactSection.vue';

export default {
  data() {
    return {
    };
  },
  components:{
    WelcomeSection,
    ClassesSection,
    StaffSection,
    BlogSection,
    ContactSection
  }

}
</script>

<template>
    <main>
        <WelcomeSection />
        <ClassesSection />
        <StaffSection />
        <BlogSection />
        <ContactSection />
    </main>
</template>

<style scoped>

</style>