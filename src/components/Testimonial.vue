<template>
  <section id="testimonials">   
      <h3 class="text-center" style="color: #ffffff">Testimonials</h3>
      <!-- carousels -->
      
      <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item" v-for="item in testimonials" :key="item.id" :class="item.class">
            <img class="rounded-circle shadow-1-strong mb-4" :src="item.img" width="150px">
              <div class="card container">
                <h5 style="margin-top: 1rem;">{{ item.name }}</h5>
                <p>{{ item.title }}</p>
                <p><i class="fas fa-quote-left pe-2"></i>
                  {{ item.test }}
                  <i class="fas fa-quote-right pe-2"></i>
                </p>
              </div>
          </div>
          
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"
          data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"
          data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      testimonials: [
      {
          id: 1,
          class: 'active',
          name: "Keenan Olivier",
          img: "https://i.postimg.cc/Vk4Ymx4N/Keenan.jpg",
          title: 'Front End Developer',
          test: "Nabila is a versatile individual, who always challenges herself to break barriers. She always willing and eager to learn new skills, which also gives her an edge to adapt easily to any environment. Knowing her is privilege because she always motivates those around her to do better positively. Not only does she encourages others to do better but she also open minded on hearing others constructive criticism so that she can evolve as an individual."
        },
        {
          id: 2,
          class: '',
          name: "Zoe Daniels",
          img: 'https://i.postimg.cc/NMQhVdGZ/Zoe.jpg',
          title: 'Front End Developer',
          test: "Nabila is a hard working lady with a big heart. She is organised, efficient and extremely competent with excellent rapport with people of all ages. Her communication skills are excellent no matter if you are talking about verbal or written. Her most important quality is that she always keeps herself updated with new information .Its just amazing to work with such a kind personality. I highly recommend Nabila Samsodien for any position or endeavor that she may pursue. She would be a valuable asset to your company"
        },
        {
          id: 3,
          class:'',
          name: "Oslin Johnson",
          img: 'https://i.postimg.cc/XY6sQpYz/Oslin.jpg',
          title: "Lecturer. Full stack developer",
          test: "Nabila is a very hard worker and the kind of problem solver that shines, in her ability to understand her short comings and turn it into a strength. Her ability to make others feel at ease with the help she provides and her determination to overcome anything."
        },
        {
          id: 4,
          class:'',
          name: "Sadia Alam",
          img: 'https://i.postimg.cc/yNQ5Qs53/Sadia.jpg',
          title: "Junior full stack developer",
          test: "Nabila has an incredible work ethic and finds learning new concepts and skills exciting. Her energy lights up the room in a delicate soothing way. She is curious about new things and like to ask questions. She stays motivated and handles herself well under pressure. She will a great asset to any company."
        },
        {
          id: 5,
          class:'',
          name: "Jake Jansen",
          img: 'https://i.postimg.cc/g25gXDzP/me.jpg',
          title: 'Junior full stack developer',
          test: "She is a very hard working individual, dedicated to completing tasks of any nature and does so effectively. Very outspoken and has leadership qualities. Works well in teams and communicates well."
        },
        {
          id: 6,
          class:'',
          name: "Abdul-Azeez Kemp",
          img: 'https://i.postimg.cc/cHkTQBZW/Screenshot-20221101-100639-edit-159098746871600.jpg',
          title: "Junior full stack developer ",
          test: "Nabila, she's a wonderful being, great to work with, always puts her 100% effort in working and a great team player."
        }
      ]
    }
  }
}

</script>

<style scoped>
#testimonials {
  min-height: 100vh;
}
</style>