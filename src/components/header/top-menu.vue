<template>
    <nav class="rbl-top-menu navbar navbar-expand-lg navbar-light">
        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
        <img src="../../assets/home/rbllogo.svg" width="120" alt="">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse d-flex flex-row-reverse" id="navbarNavDropdown">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <router-link to="/" class="nav-link">PROFILE<span class="sr-only">(current)</span></router-link>
                    <span class="active-uline"></span>
                    <!-- <a class="nav-link" href="#">PROFILE <span class="sr-only">(current)</span></a> -->
                </li>
                <li class="nav-item">
                    <router-link to="/" class="nav-link">SERVICES</router-link>
                    <span class="active-uline"></span>
                    <!-- <a class="nav-link" href="#">SERVICES</a> -->
                </li>
                <li class="nav-item">
                    <router-link to="/" class="nav-link">CONTACT US</router-link>
                    <span class="active-uline"></span>
                    <!-- <a class="nav-link" href="#">CONTACT US</a> -->
                </li>
            </ul>
        </div>
    </nav>
</template>
<style lang="scss">
@import "@/sass/top-menu.scss"
</style>