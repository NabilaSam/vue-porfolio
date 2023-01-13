<template>
  <NavBar/>
  <Home/>
  <About/>
  <Resume/>
  <Projects/>
  <Testimonial/>
  <Contact/>
  <router-view/>
  <Footer/>
</template>

<script>
import About from './components/About.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import Home from './components/Home.vue';
import NavBar from './components/NavBar.vue';
import Projects from './components/Projects.vue';
import Resume from './components/Resume.vue';
import Testimonial from './components/Testimonial.vue';

export default{
  name:"App",
  components:{
    NavBar,
    Footer,
    Home,
    About,
    Resume,
    Projects,
    Testimonial,
    Contact
}
}
</script>

<style>
#app {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color-scheme: white;
  background: url('https://i.postimg.cc/vBMvmyH0/2049.jpg') no-repeat center center/cover;
  background-attachment: fixed;
  
}


</style>
