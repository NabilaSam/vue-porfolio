<template>
    <nav>
        <router-link to="/"><i class="fa fa-home"></i> Home</router-link> |
        <router-link to="/about"><i class="fa fa-info"></i> About</router-link> |
        <router-link to="/resume"><i class="fa fa-briefcase"></i> Resume</router-link> |
        <router-link to="/projects"><i class="fa fa-laptop"></i> Projects</router-link> |
        <router-link to="/testimonials"><i class="fa fa-people-group"></i> Testimonials</router-link> |
        <router-link to="/contact"><i class="fa fa-phone"></i> Contact</router-link>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    nav {
  padding: 30px;
  background-color: #030701;
}

nav a {
  font-weight: bold;
  color: #f7ffd7;
}

nav a.router-link-exact-active {
  color: #76d337;
}
</style>