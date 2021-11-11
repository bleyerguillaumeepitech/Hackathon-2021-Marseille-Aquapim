<template>
  <div id="aquaponie">
    <div data-aos="fade-up" data-aos-duration="2000">
      <b-container class="col-12">
        <b-row class="d-flex justify-content-center mt-3">
          <p id="title" class="">L'AQUAPONIE</p>
        </b-row>

        <b-row class="d-flex justify-content-center schema mt-5">
          <b-col class="col-md-4">
            <div class="col1 col-12">
              <span class="ml-2">0 changement d'eau </span>
              <br />
              <span class="ml-2">0 intrant chimique </span>
              <br />
              <span class="ml-2"> Autonomie = Peu d'entretien </span>
            </div>
          </b-col>

          <b-col class="col-12 col-md-4">
            <b-img
              id="schema-gif"
              class="mx-auto"
              src="../static/schema.gif"
              fluid-grow
            />
          </b-col>

          <b-col class="d-flex align-items-end col-md-4">
            <div class="col2">
              <span> Parlement Européen: </span>
              <br />
              <span>
                "Une des 10 technologies qui pourraient changer nos vies"
              </span>
            </div>
          </b-col>
        </b-row>

        <b-row class="mt-5 ">
          <b-col class=" text-center desc px-5">
            L'aquaponie est un système qui unit la culture de plante et
            l'élevage de poissons ; les plantes sont parfois cultivées sur des
            billes d'argile, pouvant être irriguées en circuit fermé par de
            l'eau provenant d'aquarium où sont élevés les poissons. Des
            bactéries aérobies issues du substrat transforment l'ammoniaque
            contenu dans les urines et déjections des poissons en nutriments
            (nitrates notamment), directement assimilable par la végétation.
            L'eau purifiée retourne ensuite dans l'aquarium.
          </b-col>

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

<style>
@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #aquaponie {
    margin-top: 20%;
  }
  .desc {
  font-size: 5vw;
  font-family: 'Poppins-Medium';
  margin-bottom: 80px;
}
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #aquaponie {
    margin-top: 10%;
  }
  .desc {
  font-size: 1.2vw;
  font-family: 'Poppins-Medium';
}
}

h1 {
  font-family: 'Poppins-Bold';
  color: #3e602f;
}

.col1 {
  border-left-width: 1;
  border-top-style: groove;
  border-left-style: groove;
}

.col2 {
  border-bottom: groove;
  border-right: groove;
}



.schema {
  font-family: 'Poppins-Medium';
  font-size: 20px;
}

#schema-gif {
  width: 500%;
}
</style>