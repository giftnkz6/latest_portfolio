<template>
  <NavBar/>
  <router-view/>
  <FooterVue/>
</template>

<script>
  import NavBar from '@/components/NavBar.vue'
  import FooterVue from '@/components/FooterVue.vue'
  export default{
    name: 'App',
    components:{
      NavBar,
      FooterVue
    }
  }
</script>

<style>
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #DEFCF9;
  background-color:#3C84AB;
  height: 100%;
}

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');

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
