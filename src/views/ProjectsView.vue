<template>
    <main class="min-vh-100">
      <h2 class="text-center" style="color:#f2f2f2; margin-top: 2rem;">Projects I've Hosted with their corresponding github links</h2>
        <div class="container mx-auto mt-4">
            <div class="row">
              <div class="col-md-4">
                <div class="card" style="width: 18rem;" v-for="item in projects">
               <img src={{item.img}} class="card-img-top" alt="...">
               <div class="card-body">
                 <h5 class="card-title">{{item.name}}</h5>
                 <a href="{{item.hosted}}" class="projbtn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
                 <a href={{ item.github }} class="projbtn "><i class="fab fa-github"></i> Github</a>
            </div>
            </div>
         </div>
       </div>
     </div>
    </main>
</template>

<script>
    export default {
      data(){
        return{
          projects:[
            {name: "E commerce Website",
          img: url('https://i.postimg.cc/pXS4gsPj/ecomerce.png'),
          hosted: url('https://nabzjseomp.netlify.app/'),
          github: url('https://github.com/NabilaSam/JSEOMP'),},
            {name: "javascript CRUD functionality",
          img: url('https://i.postimg.cc/MpfWfc9C/Filtersection.png'),
          hosted: url('https://nabzjseomp.netlify.app/'),
          github: url('https://github.com/NabilaSam/JSEOMP'),},
            {name: "Javascript calculator",
          img: url('https://i.postimg.cc/rmF3W38D/calculator.png'),
          hosted: url('https://nabzjscalculator.netlify.app/'),
          github: url('https://github.com/NabilaSam/JSCalculator'),},
            {name: "Netflix",
          img: url('https://i.postimg.cc/bNV2xtpL/Capture.png'),
          hosted: url('https://nabznetflix.netlify.app/'),
          github: url('https://github.com/NabilaSam/HTML-lesson-1'),},
            {name: "First porfolio",
          img: url('https://i.postimg.cc/bYF0qMWm/firstportfolio.png'),
          hosted: url('https://nabzsamportfolio.netlify.app/index.html'),
          github: url('https://github.com/NabilaSam/nabilaPortfolio'),},
            {name: "First Carousel",
          img: url('https://i.postimg.cc/XvHqwMwh/carousel.png'),
          hosted: url('https://nabzsamportfolio.netlify.app/html/testimonial.html'),
          github: url('https://github.com/NabilaSam/nabilaPortfolio'),},
          ]
        }
      }
        
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