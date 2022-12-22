<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info.text-white
      h1 Introducción

    .row.justify-content-center.mb-5
      .col-lg-3.col-8
        figure
          img(src="@/assets/curso/temas/intro/intro.png", alt="alt")
      .col-lg-9
        p.mb-4 En este componente se abordarán los conceptos y fundamentos de las herramientas de análisis de seguridad digital, la valoración de los riesgos para elaborar la matriz de riesgos y el plan de tratamientos reconociendo la importancia de las reglas de negocio para la automatización y orquestación de procesos.
        .row.justify-content-center
          .col-auto
            .bg--paleYellow.px-5.py-2
              p.mb-0 A continuación se presenta un video que amplía la temática a tratar.

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
