<template>
  <NavBar/>
  <router-view/>

  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/> -->
</template>

<script>
  import NavBar from '@/components/NavBar.vue'
  // import HomeVue from '@/components/HomeVue.vue'
  // import FooterVue from '@/components/FooterVue.vue'
  export default{
    name: 'App',
    components:{
      NavBar,
      // FooterVue
    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #DEFCF9;
  background-color:#3C84AB;
}

*, ::before,
::after{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

nav {
  padding: 30px;
}


/* nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
