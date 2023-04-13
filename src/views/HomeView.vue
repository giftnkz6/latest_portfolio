<template>
  <div>
    <HomeVue/>
    <AboutVue/>
    <ResumeVue/>

  </div>
</template>

<script>
// @ is an alias to /src
import HomeVue from '@/components/HomeVue.vue'
import AboutVue from '@/components/AboutVue.vue';
import ResumeVue from '@/components/ResumeVue.vue';

export default {
  name: 'HomeView',
  components: {
    HomeVue,
    AboutVue,
    ResumeVue,
  }
}
</script>
