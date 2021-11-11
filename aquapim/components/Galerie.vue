<template>
  <div id="galerie">
    <div class="mt-5">
      <div class="text-center">
        <!-- Modification du titre -->
        <p id="title">Aquapim en image</p>
      </div>
      <b-container>
        <b-row class="mt-5 mb-3">
          <div data-aos="fade-left" data-aos-duration="2000" class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <!-- Modification de la photo dans "src" -->
            <b-img rounded fluid src="../static/2.jpg"></b-img>
          </div>
          <div data-aos="zoom-in" data-aos-duration="2000" class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <!-- Modification de la photo dans "src" -->
            <b-img rounded fluid src="../static/4.jpg"></b-img>
          </div>
          <div data-aos="fade-right" data-aos-duration="2000" class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <!-- Modification de la photo dans "src" -->
            <b-img rounded fluid src="../static/5.jpg"></b-img>
          </div>
        </b-row>

        <b-carousel
          id="carousel-fade"
          style="text-shadow: 0px 0px 2px #000"
          fade
          indicators
          img-width="1024"
          img-height="480"
        >
        <!-- Modification de la photo dans "src" -->
          <b-carousel-slide img-src="../static/6.jpg"></b-carousel-slide>
          <!-- Modification de la photo dans "src" -->
          <b-carousel-slide fluid img-src="../static/8.jpg"></b-carousel-slide>
          <!-- Modification de la photo dans "src" -->
          <b-carousel-slide img-src="../static/1.jpg"></b-carousel-slide>
        </b-carousel>
        <b-row class="mt-3 mb-3">
          <div data-aos="fade-left" data-aos-duration="1000" class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <!-- Modification de la photo dans "src" -->
            <b-img rounded fluid src="../static/3.jpg"></b-img>
          </div>
          <div data-aos="fade-up" data-aos-duration="2000" class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <!-- Modification de la photo dans "src" -->
            <b-img rounded fluid src="../static/9.jpg"></b-img>
          </div>
          <div data-aos="fade-right" data-aos-duration="1000" class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 mb-4">
            <!-- Modification de la photo dans "src" -->
            <b-img rounded fluid src="../static/7.jpg"></b-img>
          </div>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
/* aos permet d'avoir les animations présentes sur la page, doc: https://michalsnik.github.io/aos/ */
import aosMixin from '~/mixins/aos.js'

export default {
  mixins: [aosMixin],
}
</script>

<style scoped>
/* @media: permet de modifier le code pour les tablettes/mobiles */
@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #galerie {
    margin-top: 15% !important;
  }
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #galerie {
    margin-top: 10% !important;
  }
}

h2 {
  font-family: 'Poppins-Medium';
}
</style>