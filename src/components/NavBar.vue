<template>
    <nav class="navbar navbar-expand-lg bg-transparent navbar-fixed-top" style="width:100%;">
        <div class="container-fluid">
            <a class="navbar-brand navbrand" href="#">
                <img src="https://i.postimg.cc/dVSZZPqt/NA-3-fococlipping-standard.png" 
                alt="Nabila"
                width="200" height="">
            </a>
            <button class="navbar-toggler backtog" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0 ">
                    <li class="nav-item mx-2">
                        <router-link class="link" to="/" ><i class="fa fa-home"></i> Home</router-link> 
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="link" to="/about"><i class="fa fa-info"></i> About</router-link> 
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="link" to="/resume"><i class="fa fa-briefcase"></i> Resume</router-link> 
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="link" to="/projects"><i class="fa fa-laptop"></i> Projects</router-link> 
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="link" to="/testimonials"><i class="fa fa-people-group"></i> Testimonials</router-link> 
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="link" to="/contact"><i class="fa fa-phone"></i> Contact</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

.navbrand{
    color: #f2f2f2;
    margin: 0;
    padding: 0;
}
.backtog{
    background-color: #f2f2f2;
}

.backtog:hover{
    background-color: rgb(232, 99, 17);
}

nav {
    display: flex;
    position: relative;
    justify-content: space-between;
    align-items: center;
    max-height: max-content;
    background-color: #030701;
    z-index: 1;
}

.link{
    text-decoration: none;
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
    color: #f2f2f2;;
}

nav a.router-link-exact-active {
    color:  rgb(232, 99, 17);
}
nav a:hover {
    color:  rgb(232, 99, 17);
}

.web-title {
    font-size: 1.5rem;
    margin: .5rem;
    color: #f2f2f2;
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
    border-radius: 20px 50px;
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