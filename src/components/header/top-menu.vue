<template>
    <nav class="rbl-top-menu navbar navbar-expand-md navbar-light">
        <img src="../../assets/home/rbllogo.svg" width="120" alt="">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse d-md-flex flex-md-row-reverse" id="navbarNavDropdown">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <router-link to="/" class="nav-link">PROFILE<span class="sr-only">(current)</span></router-link>
                    <span class="active-uline"></span>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#our-services">SERVICES</a>
                    <span class="active-uline"></span>
                    
                </li>
                <li class="nav-item">
                    <!-- <router-link to="/" class="nav-link">CONTACT US</router-link> -->
                    <a class="nav-link" href="#contact-us">CONTACT US</a>
                    <span class="active-uline"></span>
                </li>
            </ul>
        </div>
    </nav>
</template>
<style lang="scss">
    /* @import "@/sass/_variables.scss"; */
    @import "@/scss/_main.scss";
    @import "@/scss/_top-menu.scss";
</style>