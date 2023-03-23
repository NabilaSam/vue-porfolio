<template>
  <NavBar/>
  <router-view/>
  <Footer/>
</template>

<script>
import Footer from './components/Footer.vue';
import NavBar from './components/NavBar.vue';

export default{
  name:"App",
  components:{
    NavBar,
    Footer
}
}
</script>

<style>
#app {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background: url('https://i.postimg.cc/vBMvmyH0/2049.jpg') no-repeat center center/cover;
  background-attachment: fixed;
  
}


</style>
