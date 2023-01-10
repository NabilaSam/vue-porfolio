<template>
  <div class="about min-vh-100">
    <h1 style="color: #f7ffd7">About Me</h1>
    <div class="card slide"> 
      I am an optimistic ,focused individual who is keen to improve and develop new skills.</div>

      <div class="card slide">I consider myself to be deadline-driven and capable of adapting to new environments.</div>

      <div class="card slide">Not only do I work well on my own, but I perform just as efficiently while in a team or under pressure</div>

      <div class="card slide">I am resilient and encouraged by challenges.</div>

      <div class="card slide">Quite comfortable with public speaking
       and taking on leadership roles if required to do so.</div>

       <div class="card slide">I am proficient in analysis and critically evaluating data</div>
  </div>
  
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.slide{
  margin: 1rem;
    box-shadow: 0 2px 4px 0 #76d337;
  animation: slidein 2s ease 0s 1 forwards; 
}
@keyframes slidein {
    from{
        transform: translateX(1244px);
    }
    to{
        transform: translateX(0px);
    }
}
</style>