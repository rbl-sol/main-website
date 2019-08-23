<template>
    <div class="homepage-wrapper ">
        <topMenu />

        <div id="bg-rbl-svg-right" class="bg-rbl-svg-orange d-none d-md-block">
            <div class="right-bg"></div>
        </div>

        <section class="get-in-touch-content">
            <div class="container section-padding">
                <div class="row">
                    <div class="col-xl-6 col-lg-6 col-md-6 col-sm-12 py-mobile-5">
                        <h1>Lorem ipsum dolor sit amet</h1>
                        <p>lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a class="button-radius rygradient">Get in touch</a>
                    </div>
                    <div class="col-xl-6 col-lg-6 col-md-6 col-sm-12">
                        <!-- <img src="./../assets/home/hero-img.svg" alt=""> -->
                        <div class="home-bg d-none d-mobile-block"></div>
                    </div>
                </div>
            </div>
        </section>

        <div id="bg-rbl-svg-home" class="d-none d-md-block">
            <div class="home-bg"></div>
        </div>

        <div id="bg-rbl-svg-left" class="bg-rbl-svg-orange d-none d-md-block">
            <div class="left-bg"></div>
        </div>

        <div class="my-divider d-none d-md-block"></div>

        <!-- our services -->
        <section class="section-header section-padding py-mobile-4" id="our-services">
            <div class="container">
                <div class="sh-title-our-services position-relative">
                    <span class="text-uppercase d-none d-md-block">Our Services</span>
                    <h2 class="text-uppercase text-center">Our Services</h2>
                </div>

                <div class="row">
                    <div class="col-lg-3 col-xl-3 col-md-3 col-sm-12 text-center">
                        <img src="./../assets/home/icon-webdev.svg" width="100" alt="web development" />
                        <h4>WEB DEVELOPMENT</h4>
                        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                            tempor incididunt ut labore et dolore
                            magna aliqua. Ut enim ad minim v</p>
                    </div>
                    <div class="col-lg-3 col-xl-3 col-md-3 col-sm-12 text-center">
                        <img src="./../assets/home/icon-webdesign.svg" width="100" alt="web design" />
                        <h4>WEB DESIGN</h4>
                        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                            tempor incididunt ut labore et dolore
                            magna aliqua. Ut enim ad minim v</p>
                    </div>
                    <div class="col-lg-3 col-xl-3 col-md-3 col-sm-12 text-center">
                        <img src="./../assets/home/icon-multimedia.svg" width="100" alt="multimedia" />
                        <h4>MULTIMEDIA</h4>
                        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                            tempor incididunt ut labore et dolore
                            magna aliqua. Ut enim ad minim v</p>
                    </div>
                    <div class="col-lg-3 col-xl-3 col-md-3 col-sm-12 text-center">
                        <img src="./../assets/home/icon-seo.svg" width="100" alt="SEO" />
                        <h4>SEO</h4>
                        <p>orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                            tempor incididunt ut labore et dolore
                            magna aliqua. Ut enim ad minim v</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- rocket line -->
        <div class="rbl-rocket-line d-none d-md-block">
            <div class="rbl-rocket-icon"></div>
        </div>

        <!-- contact us -->
        <section class="section-header section-padding py-mobile-4" id="contact-us">
            <div class="container">
                <div class="sh-title-contact-us position-relative">
                    <span class="text-uppercase d-none d-md-block">Contact Us</span>
                    <h2 class="text-uppercase text-center mb-5">Contact Us</h2>
                </div>
            </div>
            <div class="bg-footer">
                <div class="container">
                    <div class="row">
                        <div class="col-xl-8 col-lg-8 col-md-8 col-sm-12 m-auto">
                            <form action="" class="contact-us-content">
                                <div class="form-group">
                                    <input type="email" class="form-control" placeholder="Email">
                                </div>
                                <div class="form-group pt-2">
                                    <input type="text" class="form-control" placeholder="Name">
                                </div>
                                <div class="form-group py-5">
                                    <textarea name="" id="" class="form-control" cols="30" rows="10" placeholder="Message"></textarea>
                                </div>
    
                                <div class="text-center">
                                    <button class="button-radius rygradient border-0">Submit</button>
                                </div>
                            </form>
                        </div>
                    </div>

                    <!-- <div class="position-relative"> -->
                        <div class="footer container d-none d-mobile-block d-md-block">
                            <hr class="hrTopBlack1">
                            <botFooter class="my-4"/>
                        </div>  
                    <!-- </div>         -->
                </div>
            </div>
        </section>
    </div>
</template>

<script>
    import topMenu from './header/top-menu'
    import botFooter from './footer/footer'

    export default {
        name: '',
        data () {
            return {
            msg: 'Welcome to Your Vue.js App'
            }
        },
        components: {
            topMenu,
            botFooter
        }
    }
</script>

<style lang="scss">
    @import "@/scss/_variables.scss";
    @import "@/scss/_main.scss";
    @import "@/scss/_home.scss";
</style>
