<template>
    <div class="about min-vh-100">
      <h1 style="color: #f7ffd7">About Me</h1>
      <div class="card slide1"> 
        I am an optimistic ,focused individual who is keen to improve and develop new skills.</div>
  
        <div class="card slide2">
          I consider myself to be deadline-driven and capable of adapting to new environments.</div>
  
        <div class="card slide3">
          Not only do I work well on my own, but I perform just as efficiently while in a team or under pressure</div>
  
        <div class="card slide4">
          I am resilient and encouraged by challenges.</div>
  
        <div class="card slide5">
          Quite comfortable with public speaking
         and taking on leadership roles if required to do so.</div>
  
         <div class="card slide6">
          I am proficient in analysis and critically evaluating data</div>
    </div>
    
  </template>
  
  <script>
    export default {
      
    }
  </script>
  
  <style scoped>
  
  .card{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 20px;
    width: 70%;
    display: inline-block;
    margin: 1rem;
    /* box-shadow: 0 1px 2px 0 #76d337; */
    max-width: 60%;
    border-radius: 0%;
    padding-top: 0.5rem;
  }
  .slide1{
    animation: slidein 2s ease 0s 1 forwards; 
  }
  .slide2{
    animation: slidein 4s ease 0s 1 forwards; 
  }
  .slide3{
    animation: slidein 6s ease 0s 1 forwards; 
  }
  .slide4{
    animation: slidein 7s ease 0s 1 forwards; 
  }
  .slide5{
    animation: slidein 8s ease 0s 1 forwards; 
  }
  .slide6{
    animation: slidein 9s ease 0s 1 forwards;
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