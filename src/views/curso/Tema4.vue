<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:titulo="'Unidad 1. Fundamentos del Pensamiento Algorítmico'" :subTitulo="'SÍNTESIS'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      
      p(data-aos="fade-up").mb-5 La unidad I: Fundamentos del pensamiento algorítmico introduce los conceptos teóricos necesarios para comprender el diseño y la creación de algoritmos. En esta unidad, se exploran las bases de la lógica algorítmica y las estructuras básicas de pseudocódigo y diagramas de flujo, elementos clave para resolver problemas de manera sistemática. Este enfoque asegura que los estudiantes adquieran habilidades prácticas para aplicar el pensamiento algorítmico en diversos contextos, facilitando su desarrollo en áreas como la informática, administración y educación.


      .row.justify-content-center
        .col-lg-12.mb-5
          figure.bg-color-sintesis.p-5.brounded
            img(src='@/assets/curso/sintesis/sintesis.png', alt='', style="max-width: 1240px;")
  </template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.material-complementario
  padding-top: 3rem
  border-top: 9px solid $color-sistema-e
</style>
