<!-- Cette page contient le menu de navigation ainsi que son style !-->
<template>
  <div id="navbar">
    <b-navbar toggleable="lg" type="dark" variant="success">
      <!--CHANGER LOGO (b-img src="") !-->
      <b-navbar-brand class="mb-0 ml-1" href="#">
        <b-img src="../static/logo1.png" fluid alt="logo" width="100%"
      /></b-navbar-brand>
      <b-navbar-toggle target="nav-menu">
        <template #default="{ expanded }">
          <b-icon v-if="expanded" icon="menu-down"></b-icon>
          <b-icon v-else icon="menu-up"></b-icon>
        </template>
      </b-navbar-toggle>
      <b-collapse id="nav-menu" is-nav>
        <b-navbar-nav class="nav ml-auto" right>
          <!--Contient les liens de navigations vers les différentes sections !-->
          <b-nav-item href="#concept">Notre concept</b-nav-item>
          <b-nav-item href="#partenaires">Nos partenaires</b-nav-item>
          <b-nav-item href="#aquaponie">Présentation de l'aquaponie</b-nav-item>
          <b-nav-item href="#galerie">Aquapim en image</b-nav-item>
          <b-nav-item href="#equipe">L'équipe</b-nav-item>
          <b-nav-item href="#contact">Nous rejoindre </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style scoped>
@font-face {
  font-family: 'Poppins-Medium';
  src: local('Poppins-Medium'),
    url(../static/Poppins-Medium.ttf) format('truetype');
}

@font-face {
  font-family: 'Poppins-Bold';
  src: local('Poppins-Bold'), url(../static/Poppins-Bold.ttf) format('truetype');
}

.nav {
  font-family: 'Poppins-Medium';
}
</style>