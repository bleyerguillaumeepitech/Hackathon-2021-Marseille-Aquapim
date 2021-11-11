<template>
<div id="equipe">
  <div data-aos="fade-left" data-aos-duration="3000" class="mt-5">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
    
    <b-container>
      <div class="col-12 d-flex justify-content-center mt-4">
      <!-- MODIFICATION TITRE -->
      <p id="title">L'EQUIPE D'AQUAPIM</p>
    </div>
      <b-row class="justify-content-around">
        <div data-aos="zoom-in" class="col-12 col-sm-12 col-xl-4 col-md-4 mt-4 text-center">
          <!-- Modification du nom -->
          <h3 class="p-3">Theo</h3>

          <b-img fluid rounded src="../static/pdp.jpg" class="p-3"></b-img>
          <p class="détails">
            Développement commercial <br>
            Chargé de partenariats
          </p>
        </div>

        <div data-aos="zoom-in" class="col-12 col-sm-12 col-xl-4 col-md-4 mt-4 text-center">
          <!-- Modification du nom -->
          <h3 class="p-3">Guillaume</h3>

          <b-img fluid rounded src="../static/pdp2.jpg" class="p-3"></b-img>
          <p class="détails">
            Développement Produit <br>
            R&D
          </p>
        </div>
        <div data-aos="zoom-in" class="col-12 col-sm-12 col-xl-4 col-md-4 mt-4 text-center">
          <!-- Modification du nom -->
          <h3 class="p-3">Domitille</h3>

          <b-img fluid rounded src="../static/pdp3.jpg" class="p-3"></b-img>
          <p class="détails">
            Gestion de projet <br>
            Formation RH - RSE
          </p>
        </div>
      </b-row>
    </b-container>
  </div>
  </div>
</template>


<script>
import aosMixin from '~/mixins/aos.js'

export default {
  mixins: [aosMixin],
}
</script>

<style scoped>
.détails{
  font-family: 'Poppins-Light';

}
h3 {
  font-family: 'Poppins-Light';

  border-bottom: 3px solid #3e602f;
}

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #equipe {
  margin-top: 15% !important;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #equipe {
  margin-top: 10% !important;
}
}
</style>