<template>
  <div>
    <b-row align-h="center">
      <b-col id="imgZoneFlot"> </b-col>
      <b-col
        xl="7"
        lg="10"
        md="12"
        cols="12"
        align-self="center"
        class="text-center m-5"
        id="titre"
      >
        <!-- MODIFICATION TEXTE (entre balise p) -->
        <p>
          "Il ne s'agit plus seulement d'offrir de l'émerveillement mais des
          solutions concrètes à ceux qui veulent changer leur mode de vie."
        </p>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@font-face {
  font-family: 'Poppins-Medium';
  src: local('Poppins-Medium'),
    url(../static/Poppins-Medium.ttf) format('truetype');
}

#firstDiv {
  background-color: #3e602f;
}

@media all and (min-width: 319px) {
  #titre {
    font-size: 8vw;
    font-family: 'Poppins-bold';

    color: white;

    backdrop-filter: blur(6px);
    border-radius: 20px;
  }
}

@media all and (min-width: 768px) {
  #titre {
    font-size: 3vw;
    font-family: 'Poppins-bold';

    color: white;

    backdrop-filter: blur(6px);
    border-radius: 20px;
  }
}

#titre {
  position: absolute;
  z-index: 1000;
  font-family: 'Poppins-Medium';
  border-radius: 10px;
}

#titre > p {
  margin: 0;
}

#imgZoneFlot {
  /*MODIFICATION IMAGE ACCUEIL (background-image: url(' ');)*/
  background-image: url('../static/zoneflot.jpg');
  height: 900px;
  max-height: 100vh;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>