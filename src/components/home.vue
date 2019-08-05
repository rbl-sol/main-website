<template>
  <div>
    <topMenu />
  <section>
    <div class="right-bg"></div>
  </section>
  <section>
    <div class="container section-padding">
      <div class="row">
        <div class="col-sm-6 col-md-6">
          <h1>Lorem ipsum dolor sit amet</h1>
          <p>lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <a class="button-radius rygradient">Get in touch</a>
        </div>
        <div class="col-sm-6 col-md-6"></div>
      </div>
    </div>
  </section>
  <section>
    <div class="home-bg"></div>
  </section>
  <section>
    <div class="left-bg"></div>
  </section>
  <section class="container section-padding" id="our-services">
    <div class="header-our-service">
      <span class="">OUR SERVICES</span>
      <h2>OUR SERVICES</h2>
      
    </div>
    
    <div class="row">
      <div class="col-sm-3 col-md-3 text-center">
        <img src="./../assets/home/icon-webdev.svg" width="100" alt="web development" />
        <h4>WEB DEVELOPMENT</h4>
        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore
          magna aliqua. Ut enim ad minim v</p>
      </div>
      <div class="col-sm-3 col-md-3 text-center">
        <img src="./../assets/home/icon-webdesign.svg" width="100" alt="web design" />
        <h4>WEB DESIGN</h4>
        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore
          magna aliqua. Ut enim ad minim v</p>
      </div>
      <div class="col-sm-3 col-md-3 text-center">
        <img src="./../assets/home/icon-multimedia.svg" width="100" alt="multimedia" />
        <h4>MULTIMEDIA</h4>
        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore
          magna aliqua. Ut enim ad minim v</p>
      </div>
      <div class="col-sm-3 col-md-3 text-center">
        <img src="./../assets/home/icon-seo.svg" width="100" alt="SEO" />
        <h4>SEO</h4>
        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore
          magna aliqua. Ut enim ad minim v</p>
      </div>
    </div>
  </section>
  <section class="container section-padding">

  </section>
  </div>
</template>

<script>
import topMenu from './header/top-menu'

export default {
  name: '',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    topMenu
  }
}
</script>
<style lang="scss">
@import "@/sass/home.scss";
  
</style>
