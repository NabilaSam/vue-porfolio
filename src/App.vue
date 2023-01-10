<template class="background">
  <NavBar/>
  <router-view/>
</template>

<script>
import NavBar from './components/NavBar.vue';

export default{
  name:"App",
  components:{
    NavBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #030701;
  color-scheme: white;
}

.background{
  background-color: #030701;
  /* background: url(https://i.postimg.cc/W1cxQ1z7/pexels-photo-1933317.jpg);
  height: 100vh; */
}

</style>
