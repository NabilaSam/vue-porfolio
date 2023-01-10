<template>
  <section id="experience" class="body2">
    <h3
      style="text-align: center;
        margin-top: 2rem;
        text-shadow: 0.5px 0.5px black;
      "
    >
      Education & Experience
    </h3>
    <ul
      class="timeline"
      style="margin-top: 2rem;
        text-shadow: 0.2px 0.5px rgb(0, 0, 0);
        margin-left: 0.5rem;
        margin-right: 0.5,
      "
    >
    <li class="timeline" v-for="details in resume">
        <div class="timeline-badge"><i class="fas fa-atom"></i></div>
        <div class="timeline-panel">
          <div class="timeline-heading">
            <h4 class="timeline-title">{{ details.name }}</h4>
            <h6>
              Employer: <br />
              <i class="fas fa-university"></i> The University of the Western
              Cape
            </h6>
            <p>
              <small style="color: rgb(27, 25, 25)"
                ><i class="fa fa-calendar"></i> {{ details.period }}</small
              >
            </p>
          </div>
          <div class="timeline-body">
            <p>
              {{ details.description }}
            </p>
          </div>
        </div>
      </li>
    </ul>
  </section>
</template>

<script>
   export default {
        resume: "left-timeline",
        data(){
            return{
                resume:[
                    {
                        name: 'Life Choices Coding Academy',
                        period: ' September 2022 – Present',
                        description: "This bootcamp has introduced me to html, css, bootstrap, javascript and vue.js. I've had the opportunity to design and create webpages (such as this one)."
                    },
                    {
                        name: 'BSc Chemical Science degree',
                        period: ' 2018 – 2021',
                        description: "Four years worth of practical laboratory experience, research, scientific report writing, high accuracy measurements and data analysis"
                    },

                    {
                        name: '',
                        period: ' September 2022 – Present',
                        description: "This bootcamp has introduced me to html, css, bootstrap, javascript and vue.js. I've had the opportunity to design and create webpages (such as this one)."
                    }

                ]
            }
        },
        resume: "right-timeline",
        data(){
            return{
                resume:[
                    {
                        name: 'Life Choices Coding Academy',
                        period: ' September 2022 – Present',
                        description: "This bootcamp has introduced me to html, css, bootstrap, javascript and vue.js. I've had the opportunity to design and create webpages (such as this one)."
                    },
                    {
                        name: 'BSc Chemical Science degree',
                        period: ' 2018 – 2021',
                        description: "Four years worth of practical laboratory experience, research, scientific report writing, high accuracy measurements and data analysis"
                    },

                    {
                        name: '',
                        period: ' September 2022 – Present',
                        description: "This bootcamp has introduced me to html, css, bootstrap, javascript and vue.js. I've had the opportunity to design and create webpages (such as this one)."
                    }

                ]
            }
        }
    }
</script>

<style scoped>
.timeline {
  list-style: none;
  padding: 20px 0 20px;
  position: relative;
  color: black;
}
.timeline:before {
  top: 0;
  bottom: 0;
  position: absolute;
  content: " ";
  width: 3px;
  background-color: #ffffff;
  left: 50%;
  margin-left: -1.5px;
}
.timeline > li {
  margin-bottom: 20px;
  position: relative;
}
.timeline > li:before,
.timeline > li:after {
  display: table;
}
.timeline > li:after {
  clear: both;
}
.timeline > li:before,
.timeline > li:after {
  content: " ";
  display: table;
}
.timeline > li:after {
  clear: both;
}
.timeline > li > .timeline-panel {
  width: 46%;
  float: left;
  border: 1px solid #d4d4d4;
  border-radius: 2px;
  background-color: rgb(248, 242, 242, 0.8);
  padding: 20px;
  position: relative;
  -webkit-box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.175);
  box-shadow: 0 1px 6px rgba(0, 0, 0, 0.175);
}

/* Arrow between timeline and cards */
.timeline > li > .timeline-panel:before {
  position: absolute;
  top: 26px;
  right: -15px;
  display: inline-block;
  border-top: 15px solid transparent;
  border-left: 15px solid #ccc;
  border-right: 0 solid #ccc;
  border-bottom: 15px solid transparent;
  content: " ";
}
.timeline > li > .timeline-panel:after {
  position: absolute;

  top: 27px;
  right: -14px;
  display: inline-block;
  border-top: 14px solid transparent;
  border-left: 14px solid #fff;
  border-right: 0 solid #fff;
  border-bottom: 14px solid transparent;
  content: " ";
}

/* The circle on the timeline */
.timeline > li > .timeline-badge {
  color: rgb(0, 0, 0);
  width: 50px;
  height: 50px;
  line-height: 50px;
  font-size: 1.4em;
  text-align: center;
  position: absolute;
  top: 16px;
  left: 50%;
  margin-left: -25px;
  background-color: #999999;
  z-index: 100;
  border-top-right-radius: 50%;
  border-top-left-radius: 50%;
  border-bottom-right-radius: 50%;
  border-bottom-left-radius: 50%;
}

/* Shifts cards to the right side of timeline */
.timeline > li.timeline-inverted > .timeline-panel {
  float: right;
}

.timeline > li.timeline-inverted > .timeline-panel:before {
  border-left-width: 0;
  border-right-width: 15px;
  left: -15px;
  right: auto;
}

.timeline > li.timeline-inverted > .timeline-panel:after {
  border-left-width: 0;
  border-right-width: 14px;
  left: -14px;
  right: auto;
}
.timeline-badge {
  background-color: #76d337 !important;
}
.timeline-title {
  margin-top: 0;
  color: black;
}
.timeline-body > p,
.timeline-body > ul {
  margin-bottom: 0;
}
.timeline-body > p + p {
  margin-top: 5px;
}
</style>
