<template>
  <div>
    <HomeVue/>
    <AboutVue/>
    <ResumeVue/>
    <SkillVue/>
    <ProjectVue/>
    <TestimonialVue/>
    <ContactVue/>

  </div>
</template>

<script>
// @ is an alias to /src
import HomeVue from '@/components/HomeVue.vue'
import AboutVue from '@/components/AboutVue.vue';
import ResumeVue from '@/components/ResumeVue.vue';
import SkillVue from '@/components/SkillVue.vue';
import ProjectVue from '@/components/ProjectVue.vue';
import TestimonialVue from '@/components/TestimonialVue.vue';
import ContactVue from '@/components/ContactVue.vue'

export default {
  name: 'HomeView',
  components: {
    HomeVue,
    AboutVue,
    ResumeVue,
    SkillVue,
    ProjectVue,
    TestimonialVue,
    ContactVue
  }
}
</script>
