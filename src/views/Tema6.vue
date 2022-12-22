<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 6
      h1 Riesgos

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-lg-10
        .bg--piel.p-4.br_01.mb-4
          .row.justify-content-center.align-items-center
            .col-lg-7.mb-3.mb-lg-0
              p En términos generales, el riesgo se asocia a una “Contingencia o proximidad de un daño”. RAE (2021). Cuando se realiza un análisis de riesgos de ciberseguridad, lo que se pretende es encontrar cuál es la proximidad o probabilidad de que los riesgos, amenazas y vulnerabilidades, afecten los activos de información y generen un impacto adverso en la organización.
            .col-lg-5
              figure
                img(src='@/assets/curso/temas/t6/t6_01.png', alt='imagen decorativa') 

        p(data-aos="fade-left") Se debe visualizar atentamente y con sentido crítico el vídeo que se comparte a continuación. En este se podrá ampliar los conocimientos en lo relacionado con los riesgos de la ciberseguridad:

    figure(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/QLWc_y6HMuA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 
      

</template>

<script>
export default {
  name: 'Tema6',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
