<template>
  <div>
    <HomeVue/>
    <AboutVue/>

  </div>
</template>

<script>
// @ is an alias to /src
import HomeVue from '@/components/HomeVue.vue'
import AboutVue from '@/components/AboutVue.vue';

export default {
  name: 'HomeView',
  components: {
    HomeVue,
    AboutVue,
  }
}
</script>
