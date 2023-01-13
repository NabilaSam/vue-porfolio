<template>
  <section id="testimonials">   
      <h3 class="text-center">Testimonials</h3>
      <b><p class="text-center" style="color: black;">Feel free to scroll using your keyboard</p></b>
      <!-- carousels -->
      
      <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active" v-for="item in testimonialsActive" :key="item.id">
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
          <div class="carousel-item" v-for="items in testimonials" :key="items.id">
            <img class="rounded-circle shadow-1-strong mb-4" :src="items.img" width="150px">
              <div class="card container">
                <h5 style="margin-top: 1rem;">{{ items.name }}</h5>
                <h6>{{ items.title }}</h6>
                <p><i class="fas fa-quote-left pe-2"></i>
                  {{ items.test }}
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
      testimonialsActive: [
        {
          id: 1,
          name: "Keenan Olivier",
          img: 'https://i.postimg.cc/Vk4Ymx4N/Keenan.jpg',
          title: 'Front End Developer',
          test: "Nabila is a versatile individual, who always challenges herself to break barriers. She always willing and eager to learn new skills, which also gives her an edge to adapt easily to any environment. Knowing her is privilege because she always motivates those around her to do better positively. Not only does she encourages others to do better but she also open minded on hearing others constructive criticism so that she can evolve as an individual."
        }
      ],
      testimonials: [
        {
          id: 2,
          name: "Zoe Daniels",
          img: 'https://i.postimg.cc/NMQhVdGZ/Zoe.jpg',
          title: 'Front End Developer',
          test: "Nabila is a hard working lady with a big heart. She is organised, efficient and extremely competent with excellent rapport with people of all ages. Her communication skills are excellent no matter if you are talking about verbal or written. Her most important quality is that she always keeps herself updated with new information .Its just amazing to work with such a kind personality. I highly recommend Nabila Samsodien for any position or endeavor that she may pursue. She would be a valuable asset to your company"
        },
        {
          id: 3,
          name: "Oslin Johnson",
          img: 'https://i.postimg.cc/XY6sQpYz/Oslin.jpg',
          title: "Lecturer. Full stack developer",
          test: "Nabila is a very hard worker and the kind of problem solver that shines, in her ability to understand her short comings and turn it into a strength. Her ability to make others feel at ease with the help she provides and her determination to overcome anything."
        },
        {
          id: 4,
          name: "Sadia Alam",
          img: 'https://i.postimg.cc/yNQ5Qs53/Sadia.jpg',
          title: "Junior full stack developer",
          test: "Nabila has an incredible work ethic and finds learning new concepts and skills exciting. Her energy lights up the room in a delicate soothing way. She is curious about new things and like to ask questions. She stays motivated and handles herself well under pressure. She will a great asset to any company."
        },
        {
          id: 5,
          name: "Jake Jansen",
          img: 'https://i.postimg.cc/g25gXDzP/me.jpg',
          title: 'Junior full stack developer',
          test: "She is a very hard working individual, dedicated to completing tasks of any nature and does so effectively. Very outspoken and has leadership qualities. Works well in teams and communicates well."
        },
        {
          id: 6,
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
/* .carousel {
  display: flex;
} */

/* .carousel-item {
  display: flex;
  padding: 10px;
} */

/* img {
  width: 150px;
} */
</style>