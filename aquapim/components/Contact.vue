<template>
  <div class="col-12 p-0" id="contact">
    <div id="pad" class="col-12 d-flex justify-content-center mt-4 pb-md-3">
      <!-- MODIFICATION TITRE -->
      <p id="title">CONTACT</p>
    </div>

    <div
      id="back"
      class="col-12 d-flex flex-column justify-content-center mt-2"
    >
      <div class="text-center col-12">
        <!-- MODIFICATION TEXTE CONTACT -->
        <p id="paraContact" class="col-12 mt-5">
          Si vous souhaitez être informés de nos actualités, nous vous invitons à renseigner votre adresse
          e-mail. <br />
          Nous nous engageons à ne jamais communiquer vos données personnelles.
        </p>
      </div>
      <div class="align-self-center col-12 mt-4 mb-5">
        <!-- MODIFICATION SCRIPT CONTACT -->
        <form
          method="POST"
          data-email="example@email.net"
          action="https://script.google.com/macros/s/AKfycbzmiyOusy04CXYylm_PgsLEHlZC1h2TTthE6IwXCOoFkvWcrIe2S4CsRHc6foWTfa0/exec"
        >
          <div class="input-group d-flex justify-content-center">
            <input
              class="col-6 form-control"
              style="height: 5vh"
              id="email"
              name="Email"
              type="email"
              placeholder="Email"
            />
            <button
              type="submit"
              style="height: 5vh"
              @click="reload()"
              class="btn btn-success ml-1"
            >
              Envoyer
            </button>
          </div>
        </form>
        <!-- MODIFICATION LIEN ICON -->
        <div class="col-12 mt-5 d-flex justify-content-center">
          <a href="https://www.linkedin.com/company/aquapim/"
            ><b-icon class="" icon="linkedin" style="height: 40px; width: 40px"
          /></a>
          <a href="https://www.instagram.com/aqua.pim/"
            ><b-icon
              class="ml-5"
              icon="instagram"
              style="height: 40px; width: 40px"
          /></a>
          <a href="https://www.facebook.com/aqua.pim.3"
            ><b-icon
              class="ml-5"
              icon="facebook"
              style="height: 40px; width: 40px"
          /></a>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  methods: {
    async reload() {
      setTimeout(function () {
        location.reload()
      }, 1000)
    },
  },
}
</script>

<style scoped>
@font-face {
  font-family: 'Poppins-bold';
  src: local('Poppins-bold'),
    url(../static/font/Poppins-Bold.ttf) format('truetype');
}

@font-face {
  font-family: 'Poppins-light';
  src: local('Poppins-light'),
    url(../static/font/Poppins-Light.ttf) format('truetype');
}

@font-face {
  font-family: 'Poppins-LightItalic';
  src: local('Poppins-LightItalic'),
    url(../static/font/Poppins-LightItalic.ttf) format('truetype');
}

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #pad {
    padding: 0;
    padding-bottom: 0;
  }
  #contact {
    margin-top: 15%;
  }
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #contact {
    margin-top: 10%;
  }
}

@media all and (min-width: 2559px) {
  p {
    font-size: 1.8rem;
  }
}

#paraContact {
  color: #3d4246;
  font-family: 'Poppins-LightItalic';
}

#back {
  background-color: #ece9ea;
}

a {
  text-decoration: none;
  color: black;
}
</style>