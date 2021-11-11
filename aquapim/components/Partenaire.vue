<template>
  <div id="partenaires">
    <div data-aos="zoom-in" data-aos-duration="2000" class="col-12">
      <div class="col-12 d-flex justify-content-center mt-4 pb-3">
        <!-- MODIFICATION TITRE SECTION -->
        <p id="title">NOS PARTENAIRES</p>
      </div>

      <div
        id="cardborder"
        class="
          col-12
          d-flex
          justify-content-center justify-content-md-start
          pb-3
        "
      >
        <div class="row" data-aos="slide-left" data-aos-duration="1500">
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="Epitech"
            id="titlecard"
            img-src="../static/logo_epitech.png"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://www.epitech.eu/">Site</a>
              </div>
            </template>
          </b-card>
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center"
            id="desccard"
          >
            L'école pour l'informatique et les nouvelles technologies (EPITECH) est un établissement d'enseignement supérieur privé reconnu par l'État créé en 1999 par Nicolas Sadirac formant des informaticiens. L'école appartient au groupe IONIS et est membre de son pôle « Institute of Technology ».
          </b-card-text>
        </div>
      </div>
      <div
        id="cardborder"
        class="col-12 d-flex justify-content-center justify-content-md-end pb-3"
      >
        <div class="row" data-aos="slide-right" data-aos-duration="1500">
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center orderPartenaire"
            id="desccard"
          >
            Une ville appartient à ses habitants. En prendre soin, la faire évoluer, la rendre meilleure, devrait être à la portée de tous. Vous êtes de plus en plus nombreux à vous engager dans la vie de votre quartier ou pour Paris.
          </b-card-text>
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="Mairie de Paris - écoles publiques 11ème"
            id="titlecard"
            img-src="../static/logo_paris.png"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4 orderImage"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://www.paris.fr/autour-de-l-ecole">Site</a>
              </div>
            </template>
          </b-card>
        </div>
      </div>

      <div
        id="cardborder"
        class="
          col-12
          d-flex
          justify-content-center justify-content-md-start
          pb-3
        "
      >
        <div class="row" data-aos="slide-left" data-aos-duration="1500">
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="Fondation Leopold BELLAN"
            id="titlecard"
            img-src="../static/logo_leopold.png"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://www.bellan.fr/">Site</a>
              </div>
            </template>
          </b-card>
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center"
            id="desccard"
          >
            La Fondation Léopold-Bellan est une fondation française reconnue d'utilité publique qui poursuit les œuvres de son fondateur Léopold Bellan. Elle propose autour de ses axes d'actions un volet culturel par l'organisation d'un concours de musique et d'art dramatique:le concours Léopold-Bellan.
          </b-card-text>
        </div>
      </div>
      <div
        id="cardborder"
        class="col-12 d-flex justify-content-center justify-content-md-end pb-3"
      >
        <div class="row" data-aos="slide-right" data-aos-duration="1500">
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center orderPartenaire"
            id="desccard"
          >
            ENVOLUDIA, une association de familles qui accompagne les personnes atteintes de paralysie cérébrale (IMC et polyhandicap), troubles de l'apprentissage, handicap rare, de la petite enfance à l’âge adulte. Elle gère aujourd’hui un réseau d’accueil et de rééducation de 22 établissements.
          </b-card-text>
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="Réseau ENVOLUDIA - Crèche Méli-Mélo "
            id="titlecard"
            img-src="../static/logo_envoludia.jpg"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4 orderImage"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://www.envoludia.org/">Site</a>
              </div>
            </template>
          </b-card>
        </div>
      </div>
      <div
        id="cardborder"
        class="
          col-12
          d-flex
          justify-content-center justify-content-md-start
          pb-3
        "
      >
        <div class="row" data-aos="slide-left" data-aos-duration="1500">
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="AQUIMER : le pôle des produits aquatiques "
            id="titlecard"
            img-src="../static/logo_aquimer.png"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://www.poleaquimer.com/">Site</a>
              </div>
            </template>
          </b-card>
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center"
            id="desccard"
          >
            Pole Aquimer est spécialisé dans la valorisation des produits aquatiques. Il contribue à la compétitivité des entreprises en répondant à leurs besoins, en les aidants à pérenniser et développer leurs activités grâce à la R&D et à l'amélioration des technologies. Il accompagne les entreprises dans le montage de projets jusqu'à l'obtention de financement et la mise sur le marché des nouveaux produits, services et procédés
          </b-card-text>
        </div>
      </div>
      
      <div
        id="cardborder"
        class="col-12 d-flex justify-content-center justify-content-md-end pb-3"
      >
        <div class="row" data-aos="slide-right" data-aos-duration="1500">
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center orderPartenaire"
            id="desccard"
          >
            Entrepreneurs Pour La Planète est un mouvement qui propose, via une plateforme digitale, à des chefs d’entreprises d’un territoire de les guider vers un projet environnemental dans lequel ils pourront s’investir, apporter leurs compétences et leur savoir-faire de façon bénévole sous forme de mécénat de compétences. Entrepreneurs Pour La Planète est un mouvement porté par une équipe d’ambassadeurs, tous chefs d’entreprises qui ont déjà intégrés la transition écologique.
          </b-card-text>
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="ENTREPRENEURS POUR LA PLANÈTE"
            id="titlecard"
            img-src="../static/logo_planete.png"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4 orderImage"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://entrepreneurspourlaplanete.org/">Site</a>
              </div>
            </template>
          </b-card>
        </div>
      </div>

      <div
        id="cardborder"
        class="
          col-12
          d-flex
          justify-content-center justify-content-md-start
          pb-3
        "
      >
        <div class="row" data-aos="slide-left" data-aos-duration="1500">
          <!-- MODIFICATION TITRE (title="") | MODIFICATION IMAGE (modifier la destination de l'imgage dans img-src="")-->
          <b-card
            title="APAM : Association pour la Pêche et les Activités Maritimes  "
            id="titlecard"
            img-src="../static/logo_apam.png"
            img-alt="Image"
            img-top
            class="text-center col-sm-12 col-md-4 col-lg-4"
          >
            <template #footer>
              <div class="text-center">
                <!-- MODIFICATION SITE (href="")-->
                <a href="https://www.facebook.com/APAM-Association-pour-la-P%C3%AAche-et-les-Activit%C3%A9s-Maritimes-2020040828011372/">Site</a>
              </div>
            </template>
          </b-card>
          <!-- MODIFICATION DESCRIPTION (Entre les balises b-card-text)-->
          <b-card-text
            class="col-sm-12 col-md-8 col-lg-8 d-flex align-items-center"
            id="desccard"
          >
            Depuis de nombreuses années, l’APAM travaille main dans la main avec les acteurs qui œuvrent autour de la zone marine protégée du Cap Roux, via l’Association du Cantonnement de Pêche du Cap Roux
          </b-card-text>
        </div>
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

@font-face {
  font-family: 'Poppins-light';
  src: local('Poppins-light'),
    url(../static/font/Poppins-Light.ttf) format('truetype');
}

#titlecard {
  font-family: 'Poppins-bold';
  padding-right: 0px;
  padding-left: 0px;
}

a {
  font-family: 'Poppins-light';
  color: black;
}

a:hover {
  color: black;
}

h5 {
  font-family: 'Poppins-bold';
}

p {
  font-family: 'Poppins-light';
}

@media all and (min-width: 319px) {
  #title {
    font-size: 8vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }

  #partenaires {
    margin-top: 20%;
  }
}

@media all and (max-width: 426px) {
  #cardborder {
    margin-top: 100px;
    margin-bottom: 100px;
    text-align: center;
  }
  #desccard {
    font-family: 'Poppins-light';
    font-size: 5vw;
  }
  .orderPartenaire{
    order: 2;
  }
  .orderImage{
    order: 1;
  }
}

@media all and (min-width: 768px) {
  #title {
    font-size: 3vw;
    font-family: 'Poppins-bold';
    color: #3e602f;
  }
  #partenaires {
    margin-top: 10%;
  }
  #desccard {
    font-family: 'Poppins-light';
    font-size: 1.5vw;
  }
}

#cardborder {
  margin-top: 80px;
}
</style>