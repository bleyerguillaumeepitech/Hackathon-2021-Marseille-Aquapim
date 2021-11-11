<!-- Ce fichier contient le code du bas de page !-->

<template>
  <div id="footer">
    <div>
    </div>
    <b-container fluid class="pt-3">
      <b-row class="d-flex justify-content-md-around">
        <b-row>
          <b-col class="mt-3">
            <b-col>
              <!-- Emplacement email de contact !-->
              <b-icon class="mr-2 mt-1" icon="envelope"></b-icon>
              <span>theophile.gallardo@gmail.com</span>
            </b-col>
            <b-col>
              <!-- Emplacement Numéro de téléphone !-->
              <b-icon class="mr-2 mt-1" icon="phone"></b-icon>
              <span>+33613296712</span>
            </b-col>
            <b-col>
              <b-icon icon="building" class="mr-2 mt-1"> </b-icon>
              <!-- Emplacement Adresse !-->
              <span>AQUAPIM, 69 rue du Rouet, 13008 MARSEILLE </span>
            </b-col>
          </b-col>
        </b-row>
        <b-row>
          <b-col xl="12" id="footerLinks" class="mt-3">
            <!-- Emplacement Des Sections de la Page !-->
            <b-col>
              <a class="text-white" href="#concept">Notre concept</a>
            </b-col>
            <b-col>
              <a class="text-white" href="#partenaires">Nos partenaires</a>
            </b-col>
            <b-col>
              <a class="text-white" href="#aquaponie"
                >Présentation de l'aquaponie</a
              >
            </b-col>
            <b-col>
              <a class="text-white" href="#galerie">Aquapim en image</a>
            </b-col>
            <b-col>
              <a class="text-white" href="#equipe">L'équipe</a>
            </b-col>
            <b-col>
              <a class="text-white" href="#contact">Nous rejoindre</a>
            </b-col>
          </b-col>
        </b-row>
      </b-row>

      <hr class="solid" />
      <b-row>
        <small class="mx-auto mb-2">Copyright AQUAPIM - 2021</small>
      </b-row>
    </b-container>
  </div>
</template>


<style scoped>
#footerLinks {
  font-family: 'Poppins-Medium';
}
#footer {
  background-color: rgb(65, 65, 65);
  bottom: 0;
  color: white;
  font-family: 'Poppins-Medium';
}
</style>
