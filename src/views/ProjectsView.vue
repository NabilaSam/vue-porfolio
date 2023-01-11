<template>
    <main class="min-vh-100">
      <h2 class="text-center" style="color:#f2f2f2; margin-top: 2rem;">Projects I've Hosted with their corresponding github links</h2>
        <div class="container mx-auto mt-4">
            <div class="row">
              <div class="col-md-4">
                <div class="card" style="width: 18rem;">
            <img src="../imgs/Projects/netflix home.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Dummy netflix</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Landing page</h6>
              <a href="https://nabznetflix.netlify.app/" class="projbtn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
              <a href="https://github.com/NabilaSam/HTML-lesson-1" class="projbtn "><i class="fab fa-github"></i> Github</a>
            </div>
            </div>
              </div>    
                 <div class="col-md-4">
          <div class="card" style="width: 18rem;">
            <img src="../imgs/Projects/netflixtables.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Netflix</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Tables</h6>
               <a href="https://nabznetflix.netlify.app/" class="projbtn  mr-2"><i class="fas fa-link"></i> Hosted Site</a>
              <a href="https://github.com/NabilaSam/HTML-lesson-1" class="projbtn"><i class="fab fa-github"></i> Github</a>
            </div>
            </div>
              </div>    
                    <div class="col-md-4">
          <div class="card" style="width: 18rem;">
            <img src="../imgs/Projects/netflixtabs.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Same Netflix</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Different tab</h6>
             <a href="https://nabznetflix.netlify.app/" class="projbtn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
              <a href="https://github.com/NabilaSam/HTML-lesson-1" class="projbtn "><i class="fab fa-github"></i> Github</a>
            </div>
            </div>
            </div>
              
              <div class="col-md-4">
                <div class="card" style="width: 18rem;">
            <img src="../imgs/Projects//netflixwatch.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Netflix again</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Watch options</h6>
              <a href="https://nabznetflix.netlify.app/" class="projbtn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
              <a href="https://github.com/NabilaSam/HTML-lesson-1" class="projbtn"><i class="fab fa-github"></i> Github</a>
            </div>
            </div>
              </div>    
                 <div class="col-md-4">
          <div class="card" style="width: 18rem;">
            <img src="../imgs/Projects//carouselyoga.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Yoga</h5>
                  <h6 class="card-subtitle mb-2 text-muted">First Carousel</h6>
              <a href="https://carousel-yoga.netlify.app/" class="projbtn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
              <a href="https://github.com/NabilaSam/Carousel" class="projbtn"><i class="fab fa-github"></i> Github</a>
            </div>
            </div>
              </div>    
                    <div class="col-md-4">
          <div class="card" style="width: 18rem;">
            <img src="../imgs/Projects/ID+flip cards.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Flips cards</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Including ID Card</h6>
              <a href="https://idcardandflipcards.netlify.app/" class="projbtn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
              <a href="https://github.com/NabilaSam/flipcards.git" class="projbtn"><i class="fab fa-github"></i> Github</a>
            </div>
          </div>
      </div>
                
       </div>
     </div>
    </main>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.card {
    background: #030701;
    border: 2px solid #76d337;
    color:  #f7ffd7;
    margin-bottom: 2rem;
  }
  
  .projbtn {
    border: 4px solid;
    padding: 1px;
    border-image-slice: 1;
    background: var(--gradient) !important;
    -webkit-text-fill-color: transparent !important;
    border-image-source:  var(--gradient) !important; 
    text-decoration: none;
    transition: all .4s ease;
  }
  
  .projbtn:hover{
        background: var(--gradient) !important;
    -webkit-text-fill-color: rgb(0, 0, 0) !important;
    border: 5px solid  #f7ffd7 !important; 
    box-shadow: #030701 1px 0 10px;
    text-decoration: underline;
  }
</style>