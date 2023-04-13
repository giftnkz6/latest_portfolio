<template>
  <div>
    <HomeVue/>
    <AboutVue/>
    <ResumeVue/>
    <SkillsVue/>
    <ProjectVue/>

  </div>
</template>

<script>
// @ is an alias to /src
import HomeVue from '@/components/HomeVue.vue'
import AboutVue from '@/components/AboutVue.vue';
import ResumeVue from '@/components/ResumeVue.vue';
import SkillsVue from '@/components/SkillsVue.vue';
import ProjectVue from '@/components/ProjectVue.vue';

export default {
  name: 'HomeView',
  components: {
    HomeVue,
    AboutVue,
    ResumeVue,
    SkillsVue,
    ProjectVue
  }
}
</script>
