<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 1
      h1 Técnicas de recolección de información

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t1/t1_01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las técnicas de recolección de información involucran los métodos para la captura o toma de datos que se pueden aplicar en las investigaciones o procesos de una organización, los mismos se pueden dar en forma cualitativa o cuantitativa. Es importante resaltar que en la recolección de la información se debe validar la calidad de la información y sus fuentes.

    p(data-aos="fade-left").mb-5 En la recolección de información es importante tener claridad en algunos conceptos que orientan dicho proceso. A continuación, se presentan los más destacados, para asimilarlos mejor se recomienda llevar registro de ellos en la libreta de apuntes personal: 

    .row.justify-content-center(data-aos="fade-down")
      .col-md-11.p-md-5.py-5.px-3
        .bg_img_01.p-4.br_cstm
          .row.justify-content-center
            .col-md-6.mb-4
              .content  
                .content-overlay
                img(src="@/assets/curso/temas/t1/t1_02.png", alt="Información primaria") 
                .tarjeta-details.fadeIn-top.text-center.text-white.p-1
                  h4 Información primaria
                  p Es la información que se recolecta directamente, por medio de un sujeto directo con su objeto de investigación.

            .col-md-6.mb-4
              .content(@mouseover="mostrarIndicador = false")
                .indicador--click(v-if="mostrarIndicador")  
                .content-overlay
                img(src="@/assets/curso/temas/t1/t1_03.png", alt="Información secundaria") 
                .tarjeta-details.fadeIn-top.text-center.text-white.p-1
                  h4 Información secundaria
                  p Es aquella que se recopila con base en investigaciones realizadas o fuentes de información con propósitos diferentes. La información secundaria es recolectada sin tener contacto directo con el objeto de análisis.

            .col-md-6.mb-4
              .content  
                .content-overlay
                img(src="@/assets/curso/temas/t1/t1_04.png", alt="Objeto") 
                .tarjeta-details.fadeIn-top.text-center.text-white.p-1
                  h4 Objeto
                  p Elemento, proceso, área que puede ser objeto de interacción, análisis e investigación por uno o más individuos.

            .col-md-6.mb-4
              .content  
                .content-overlay
                img(src="@/assets/curso/temas/t1/t1_05.png", alt="Sujeto") 
                .tarjeta-details.fadeIn-top.text-center.text-white.p-1
                  h4 Sujeto
                  p Actor o individuo que interactúa o participa con un objeto.    

    separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Técnicas de recolección más usuales

    .row.justify-content-center.mb-5
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-left")
        .topSquare.clr--pink
          .row
            .col-lg-3.col-auto
              figure
                img(src="@/assets/curso/temas/t1/t1_06.svg", alt="alt").img75.m-auto
            .col
              p.mb-0 Para el proceso de recolección de la información, con fines de análisis y valoración de riesgos en ciberseguridad, existen distintas técnicas. Estas técnicas de recolección de información pueden ser aplicadas en diversos ámbitos y contextos. Tener un conocimiento suficiente de las mismas es importante para levantar los datos e información necesarios, que aseguren un proceso de análisis de riesgos de ciberseguridad más efectivo y cierto.
      .col-lg-5(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/t1/t1_07.png", alt="alt")

    p(data-aos="fade-left").mb-5 Para profundizar en las técnicas de recolección más usuales, se encontrará una explicación con detalle en el siguiente recurso:

    .bg_cta.p-3.mb-5(data-aos="zoom-in")
      .row.justify-content-around.align-items-center
        .col-auto
          img(src="@/assets/curso/temas/recursos/cta_01.svg").img75
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0              
              p.text-white.mb-0 Afiance los aspectos más importantes de este punto, explorando conscientemente el recurso que aquí le presentamos; recuerde llevar registro en su libreta personal de apuntes. ¡Adelante!  
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('/downloads/Tecnicas_Recoleccion.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

    separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Características de las técnicas de recolección

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/t1/t1_08.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las técnicas de recolección de información involucran los métodos para la captura o toma de datos que se pueden aplicar en las investigaciones o procesos de una organización, los mismos se pueden dar en forma cualitativa o cuantitativa. Es importante resaltar que en la recolección de la información se debe validar la calidad de la información y sus fuentes.

    p(data-aos="fade-left").mb-5 Las técnicas de recolección de información pueden apropiar las características que se descubrirán en el recurso que se muestra a continuación. ¡Adelante!

    .bg--paleYellow.br_01.p-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Técnicas Cualitativas
            p Pueden presentar alto nivel de entendimiento de los datos e información. La relevancia está dada en las respuestas individuales y su nivel de profundidad. Tienen un alto nivel de subjetividad y dependen del conocimiento, experiencia y percepción que un sujeto tiene sobre el objeto de estudio.
          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t1/t1_09.png', alt='')

        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Técnicas Cuantitativas
            p Su base fundamental son los datos numéricos, que representan características o detalles particulares de un objeto de estudio. Una gran cantidad de datos sobre uno o más atributos, de un objeto de estudio, que permita generalizar en los resultados obtenidos, facilitando la comprensión y toma la de decisiones.
          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t1/t1_10.png', alt='')

        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Registro de datos
            p Consiste en el proceso de recopilar los datos o información obtenida, cuando se aplican las técnicas de recolección de información. Este es un elemento importante que puede ser aplicado tanto en papel y archivos físicos, como en medios digitales, tales como: documentos de procesadores de texto, registros multimedia (imagen, audio, video), aplicaciones de software y bases de datos digitales.
          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t1/t1_11.png', alt='')
        



    
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
