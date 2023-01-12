<template>
    <div>
      <VueSlickCarousel>
        <div v-for="test in testimonials">
        <img src="{{ test.img }}" alt="">
      </div>
      </VueSlickCarousel>
        
    </div>
</template>

<script>
      import VueSlickCarousel from 'vue-slick-carousel'
      import 'vue-slick-carousel/dist/vue-slick-carousel.css'
    
      import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
    data(){
        return{
          testimonials:[
            {name: "Keenan Olivier",
          img: 'https://i.postimg.cc/Vk4Ymx4N/Keenan.jpg',
          title: 'Front End Developer',
          Test: "Nabila is a versatile individual, who always challenges herself to break barriers. She always willing and eager to learn new skills, which also gives her an edge to adapt easily to any environment. Knowing her is privilege because she always motivates those around her to do better positively. Not only does she encourages others to do better but she also open minded on hearing others constructive criticism so that she can evolve as an individual."
        },
            {name: "Zoe Daniels",
          img: 'https://i.postimg.cc/NMQhVdGZ/Zoe.jpg',
          title: 'Front End Developer',
          Test: "Nabila is a hard working lady with a big heart. She is organised, efficient and extremely competent with excellent rapport with people of all ages. Her communication skills are excellent no matter if you are talking about verbal or written. Her most important quality is that she always keeps herself updated with new information .Its just amazing to work with such a kind personality. I highly recommend Nabila Samsodien for any position or endeavor that she may pursue. She would be a valuable asset to your company"
        },
            {name: "Oslin Johnson",
          img: 'https://i.postimg.cc/XY6sQpYz/Oslin.jpg',
          title: "Lecturer. Full stack developer",
          Test: "Nabila is a very hard worker and the kind of problem solver that shines, in her ability to understand her short comings and turn it into a strength. Her ability to make others feel at ease with the help she provides and her determination to overcome anything."
        },
            {name: "Sadia Alam",
          img: 'https://i.postimg.cc/yNQ5Qs53/Sadia.jpg',
          title: "Junior full stack developer",
          Test: "Nabila has an incredible work ethic and finds learning new concepts and skills exciting. Her energy lights up the room in a delicate soothing way. She is curious about new things and like to ask questions. She stays motivated and handles herself well under pressure. She will a great asset to any company."
        },
            {name: "Jake Jansen",
          img: 'hhttps://i.postimg.cc/g25gXDzP/me.jpg',
          title: 'Junior full stack developer',
          Test: "She is a very hard working individual, dedicated to completing tasks of any nature and does so effectively. Very outspoken and has leadership qualities. Works well in teams and communicates well."
        },
            {name: "Abdul-Azeez Kemp",
          img: 'https://i.postimg.cc/cHkTQBZW/Screenshot-20221101-100639-edit-159098746871600.jpg',
          title: "Junior full stack developer ",
          Test: "Nabila, she's a wonderful being, great to work with, always puts her 100% effort in working and a great team player."
        }
      ]
    }
  }
}
</script>

<style scoped>
    
</style>