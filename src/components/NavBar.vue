<template>
    <nav class="navbar navbar-expand-lg bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <router-link to="/"><i class="fa fa-home"></i> Home</router-link> |

                    <router-link to="/about"><i class="fa fa-info"></i> About</router-link> |

                    <router-link to="/resume"><i class="fa fa-briefcase"></i> Resume</router-link> |

                    <router-link to="/projects"><i class="fa fa-laptop"></i> Projects</router-link> |

                    <router-link to="/testimonials"><i class="fa fa-people-group"></i> Testimonials</router-link> |

                    <router-link to="/contact"><i class="fa fa-phone"></i> Contact</router-link>

                </ul>
            </div>
        </div>
    </nav>
        <!-- </nav>
   <nav class="nav">
    <div class="web-title"><img src="https://i.postimg.cc/mgrv9Pqx/Nabila-Logo.png"></div>

      <a href="#" class="toggle-button">
            <span class="bar"></span>
            <span class="bar"></span>
            <span class="bar"></span>
          </a>
          <div class="nav-links">
            <ul>
            <router-link to="/"><i class="fa fa-home"></i> Home</router-link> |
        
            <router-link to="/about"><i class="fa fa-info"></i> About</router-link> |
        
            <router-link to="/resume"><i class="fa fa-briefcase"></i> Resume</router-link> |
        
            <router-link to="/projects"><i class="fa fa-laptop"></i> Projects</router-link> |
        
            <router-link to="/testimonials"><i class="fa fa-people-group"></i> Testimonials</router-link> |
        
            <router-link to="/contact"><i class="fa fa-phone"></i> Contact</router-link>
       
            </ul>
            </div>
   </nav> -->
</template>

<script>
export default {

}
</script>

<style scoped>
nav {
    display: flex;
    position: relative;
    justify-content: space-between;
    align-items: center;
    max-height: max-content;
    background-color: #030701;
}


.navbar-links {
    height: 100%;
}

.navbar-links ul {
    margin: 0;
    padding: 0;
    display: flex;
}

.navbar-links li {
    list-style: none;
}

.navbar-links li a {
    text-decoration: none;
    padding: 1rem;
    display: block;
}

.navbar-links li:hover {
    background-color: grey;
}

nav a {
    font-weight: bold;
    color: #f7ffd7;
}

nav a.router-link-exact-active {
    color: #76d337;
}

.web-title {
    font-size: 1.5rem;
    margin: .5rem;
}

.toggle-button {
    position: absolute;
    top: .75rem;
    right: 1rem;
    display: none;
    flex-direction: column;
    justify-content: space-between;
    width: 30px;
    height: 21px;
}

.toggle-button .bar {
    height: 3px;
    width: 100%;
    background-color: #f2f2f2;
    border-radius: 10px;
}


@media screen and (max-width: 650px) {
    header {
        width: 100% !important;
    }

    .toggle-button {
        display: flex;
    }

    .navbar-links {
        display: none;
        width: 100%;
    }

    .nav {
        flex-direction: column;
        align-items: flex-start;
    }

    .nav-links ul {
        flex-direction: column;
        width: 100%;

    }

    .navbar-links li {
        text-align: center;

    }

    .navbar-links li a {
        padding: 0.5rem 1rem;
    }

    .navbar-links.active {
        display: flex;
    }


    .name {
        font-size: 1rem;
        text-transform: bold;
        color: black;
    }

}
</style>