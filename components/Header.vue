header
<template lang="pug">
  section.hero.is-success
    .hero-head
      header.navbar
        .container
          .navbar-left
              .navbar-item
              strong platzi Music
          .navbar-end.navbar-menu
            router-link.navbar-item(to="search") Buscar
            router-link.navbar-item(to="About") Nosotros
    .hero-body
      .container.has-text-centered
        h1.title Platzi Music
        h2.subtitle Canciones que están Vue-nísimas
</template>