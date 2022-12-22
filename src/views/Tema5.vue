<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 5
      h1 Inventario de activos y evaluación de impacto de riesgos

    .row.justify-content-center
      .col-lg-7.order-2.order-lg-1(data-aos="fade-left")
        p El inicio del análisis de riesgos en ciberseguridad, una vez que se haya apropiado una metodología de riesgos, es empezar por el inventario de activos de información y, a partir de allí, valorar la importancia de los mismos, los riesgos asociados, controles y determinación del riesgo inherente y residual, concluyendo con el establecimiento de un plan de tratamiento de riesgos.
      .col-lg-5.col-8.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/t5/t5_01.png', alt='imagen decorativa') 


    .row.justify-content-center.py-5(data-aos="zoom-in")
      .col-lg-10
        .bg_cta.p-4
          .row.justify-content-center.align-items-center.p-md-5.p-4
            .col-lg-5.col-8.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/t5/t5_02.svg', alt='imagen decorativa')
            .col-lg-7.mb-4.mb-md-0
              .titulo-segundo.color-acento-contenido.mb-4
                .h3.text-white Inventario de activos y evaluación de impacto de riesgos
              p.text-white.mb-4 Estudie este punto, a profundidad, en el Anexo. Analice, uno a uno, los elementos conceptuales y operativos que allí se muestran y, de ser posible, tome nota en su libreta personal de apuntes.
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Inventario_Activos.pdf')" target="_blank" type="application/pdf")
                span Descargar
                i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema5',
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
