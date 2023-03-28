<template>
    <section class="body">
            <!-- landing page -->
            <div class="min-vh-100">
                <div class="grid-container">
                <!-- Slide In Id Card -->
               <div >
                   <div class="cardtestimonial">
                     <img
                       src="https://i.postimg.cc/VsZwfQqb/IMG-20221013-131514.jpg"
                       alt="profilepic"
                       style="width: 60%"
                     />
                     <h2 class="card_header">Nabila Samsodien</h2>
                     <p class="title" 
                     style="color: rgb(255, 255, 255);
                     background-color: rgba(0,0,0,0.3);">
                       <br>
                       <b>
                       Intern Web Developer
                    <br>
                &
            <br>
        Chemical Scientist</b>
                     </p>
                     <div>
                       
                     </div>
                  </div>
             </div>
              <!-- fade in Landing text -->
             <div class="animate__animated animate__fadeIn animate__delay-2s">
                <h3  style="color: #f2f2f2; text-shadow: 2px 2px black;"> WHAT CAN I CREATE FOR YOU? </h3>
             </div>
         </div>
        </div>
      </section>  
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

    /* My landing page Grid */
.grid-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
  }
  .grid-container>div:nth-child(1) {
    grid-column: 1/2;
    grid-row: 1/3;
  }
  .grid-container>div:nth-child(2) {
    grid-column: 2/4;
    grid-row: 2/3;
  }



/* Slide in ID card */

.cardtestimonial{
    border-radius: 5px;
    padding: 1rem;
    text-align: center;
    background-color: transparent;
    margin-top: 10%;
    box-shadow: 0 4px 8px 0 #f2f2f2;
    padding: 20px;
    margin: 20px;
    text-align: center;
    font-family: sans-serif;
    float: left;
    animation: slidein 2s ease 0s 1 forwards; 
    max-width: 300px;
}

@keyframes slidein {
    from{
        transform: translateX(1244px);
    }
    to{
        transform: translateX(0px);
    }
}

.landing{
       min-height: 100vh;
    }
</style>

