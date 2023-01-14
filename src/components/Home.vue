<template>
    <div id="home" class="container landing" style="margin-top:20%;">
        <h1>Hi, Welcome to Nabila Samsodien's portfolio</h1>

        <button class="btn btn-rounded"> <a href="#projects"> View projects</a></button>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

    h1{
        color: #f2f2f2;

    }
    .landing{
       min-height: 100vh;
    }

    button a{
        text-decoration: none;
        background-color: #030701;
        color: #f7ffd7;
        border: 4px solid;
        padding: 2px;
        text-decoration: none;
        border-image: linear-gradient( to bottom right, #76d337,  #030701);
        border-color: linear-gradient( to bottom right, #76d337,  #030701);
 }

    button a:hover{
        background:linear-gradient( to bottom right, #76d337,  #030701); ;
  
    }
</style>