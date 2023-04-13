<template>
  <div class="home">
    <div class="circle1"></div>

    <h1>HELLO I'M GIFT THE CREATOR</h1>

    <h2>I AM A WEB DEVELOPER INTERN</h2>
    <div class="p">
      <p>I create great and amazing websites made in my image and I can help you create websites made in your image. I design interactive and responsive websites.
      </p>
      
    </div>

    <div class="circle2"></div>

    <button class="btn btn-info">Contact me</button>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>

<style scoped>

.p{
  width: 35rem;
  margin: auto;
  margin-top: 1rem;
}
.circle1{
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: #D9D9D9;
  mask-position: absolute;
  opacity: 50%;
  margin-top: 1rem;
  margin-left: 2rem;
}

button{
  width: 10rem;
  height: 4rem;
  /* background-color: #85CDFD; */
  color: #DEFCF9;
  /* border-radius: 6%; */
  font-size: larger;
}
.circle2{
  width: 100px;
  height: 100px;
  margin-top: 1rem;
  border-radius: 50%;
  background-color: #D9D9D9;
  opacity: 50%;
  margin-left: 70rem;
}
.home{
  min-height: 100vh;
}
h2{
  color: #DEFCF9;
  margin-top: 1rem;
}
h1{
  color: #DEFCF9;
  font-size: 4rem;
  margin-bottom: 2rem;
}
</style>
