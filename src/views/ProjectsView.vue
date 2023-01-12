<template>
    <main class="min-vh-100">
      <h2 class="text-center" style="color:#f2f2f2; margin-top: 2rem;">Projects I've Hosted with their corresponding github links</h2>
        <div class="row container" style="margin:auto;">
              <div class="col-sm-3 mx-5" v-for="item in projects">
                <div class="card" style="width: 18rem;">
               <img :src='item.img' class="card-img-top image" alt="...">
               <div class="card-body">
                 <h5 class="card-title">{{item.name}}</h5>
                 <a :href="item.hosted" class="projbtn mr-2" style="float:left;"><i class="fas fa-link"></i> Hosted Site </a>
                 <a :href="item.github" class="projbtn " style="float:right;"><i class="fab fa-github"></i> Github</a>
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
          img: 'https://i.postimg.cc/pXS4gsPj/ecomerce.png',
          hosted: 'https://nabzjseomp.netlify.app/',
          github: 'https://github.com/NabilaSam/JSEOMP',},
            {name: "javascript CRUD functionality",
          img: 'https://i.postimg.cc/MpfWfc9C/Filtersection.png',
          hosted: 'https://nabzjseomp.netlify.app/',
          github: 'https://github.com/NabilaSam/JSEOMP',},
            {name: "Javascript calculator",
          img: 'https://i.postimg.cc/rmF3W38D/calculator.png',
          hosted: 'https://nabzjscalculator.netlify.app/',
          github: 'https://github.com/NabilaSam/JSCalculator',},
            {name: "Netflix",
          img: 'https://i.postimg.cc/bNV2xtpL/Capture.png',
          hosted: 'https://nabznetflix.netlify.app/',
          github: 'https://github.com/NabilaSam/HTML-lesson-1',},
            {name: "First portfolio",
          img: 'https://i.postimg.cc/bYF0qMWm/firstportfolio.png',
          hosted: 'https://nabzsamportfolio.netlify.app/index.html',
          github: 'https://github.com/NabilaSam/nabilaPortfolio',},
            {name: "First Carousel",
          img: 'https://i.postimg.cc/XvHqwMwh/carousel.png',
          hosted: 'https://nabzsamportfolio.netlify.app/html/testimonial.html',
          github: 'https://github.com/NabilaSam/nabilaPortfolio',},
          ]
        }
      }
        
    }
</script>

<style scoped>

main{
  margin: 0;
  padding: 0;
}

.image{
  opacity: 30%;
}

.image:hover{
  opacity: 100%;
}
.card {
    background: #030701;
    border: 2px solid #76d337;
    color:  #f7ffd7;
    margin-bottom: 2rem;
    opacity: 0.5 black;
  }
  
  .card-body a{
    color: #f7ffd7;
    border: 4px solid;
    padding: 2px;
    text-decoration: none;
    border-image: linear-gradient( to bottom right, #76d337,  #030701);
    border-color: linear-gradient( to bottom right, #76d337,  #030701);
  }

  .card-body a:hover{
    background:linear-gradient( to bottom right, #76d337,  #030701); ;
  }

  col{
    display: flex;
  }
</style>