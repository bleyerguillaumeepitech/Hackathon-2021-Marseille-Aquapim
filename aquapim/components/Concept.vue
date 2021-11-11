<template>
<div id="concept">
    <div data-aos="flip-up" data-aos-duration="1500" class="col-12" id="">
      <div class="col-12 d-flex justify-content-center mt-4 pb-3">
        <!-- MODIFICATION TITRE -->
        <p id="title">NOTRE CONCEPT</p>
      </div>

      <div class="col-12 d-flex justify-content-center mt-2">
        <!-- MODIFICATION IMAGE (modifier la destination de l'imgage dans src="") -->
        <img class="img-fluid" src="../static/Concept.png" >
      </div>
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

@font-face {
  font-family: 'Poppins-bold';
  src: local('Poppins-bold'),
    url(../static/font/Poppins-Bold.ttf) format('truetype');
}

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #concept {
  margin-top: 10%;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #margtop {
  margin-top: 10%;
}
}
</style>