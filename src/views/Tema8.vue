<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 8
      h1 Matriz de riesgos

    p(data-aos="fade-left").mb-4 La matriz de riesgos se construye a partir de las evaluaciones de activos, probabilidad de riesgos, el impacto, controles y el riesgo residual. La matriz de riesgos permite tener la trazabilidad necesaria del resultado de análisis de un riesgo o de un activo de información.

    .row
      .col-lg-5.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/t8/t8_01.png', alt='imagen decorativa')  

      .col-lg-7(data-aos="fade-left")
        .bg--piel.br_cstm.p-4
          p La matriz debe contener un registro y valoración de:
          ul.lista-ul--color.lista-acento-botones.mb-0
            li.mb-0 
              i.fas.fa-square
              | Activos de información.
            li.mb-0 
              i.fas.fa-square
              | Riesgos; (Amenazas, principios afectados por amenazas, elementos vulnerables).
            li.mb-0 
              i.fas.fa-square
              | Probabilidad de riesgos.
            li.mb-0 
              i.fas.fa-square
              | Dimensiones de Impactos organizacionales.
            li.mb-0 
              i.fas.fa-square
              | Cálculo del Riesgo inherente.
            li.mb-0 
              i.fas.fa-square
              | Controles y aplicación de controles al catálogo de riesgos.
            li.mb-0 
              i.fas.fa-square
              | Cálculo del riesgo residual.          

    Separador
    
    #t_8_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 8.1 Diligenciamiento de la matriz de riesgos

    .row.justify-content-center(data-aos="fade-down")
      .col-md-10
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-4.mb-5
          .bloque-texto-g__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t8/t8_02.png')})`}")
          .bloque-texto-g__texto.py-5.px-4           
            p.mb-0 La matriz de riesgos se convierte en instrumento clave para lograr que la organización gestiones y determinar con la mayor objetividad, todos y cada uno de los riesgos relevantes y no relevantes, que afectarían o no, y en qué medida, la ciberseguridad y la seguridad de la información, así como también la seguridad general de la infraestructura, el talento humano, las redes de servicios, los procesos, etc.            

    p(data-aos="fade-left").mb-4 Diligenciar la matriz de riesgos, es una acción sencilla que implica analizar los procesos, funciones y tareas que, en la organización, desarrollan tanto sus colaboradores como, incluso, los activos mismos de información. Visualice y analice la referencia de matriz de riesgos que le presentamos, ver tabla 12.

    .row.justify-content-center(data-aos="zoom-in")
      .col-md-10
        .titulo-sexto.color-acento-contenido
          p.mb-0
            strong Tabla 12. 
            |  Referencia matriz de riesgos.
        .tabla-b.tabla-2.color-primario.border-diferentes.mb-2
          table  
            thead.tabla-b__header 
              tr
                th(rowspan="2") 
                  h4.text-white.mb-0 Activo
                th(colspan="4")  
                  h4.text-white.mb-0 Activo y riesgo inherente
                th(colspan="5") 
                  h4.text-white.mb-0 Elementos vulnerables asociados 
              tr
                th.rojo
                  p.text-white.mb-0 Valor activo
                th.rojo
                  p.text-white.mb-0 Probabilidad Total
                th.rojo
                  p.text-white.mb-0 Impacto General
                th.rojo
                  h5.text-white.mb-0 Riesgo Inherente
                th.rojo2
                  p.text-white.mb-0 Controles      
                th.rojo2
                  p.text-white.mb-0 Nueva probabilidad
                th.rojo2
                  p.text-white.mb-0 Nuevo impacto
                th.rojo2
                  h5.text-white.mb-0 Riesgo residual      
                th.rojo2
                  h5.text-white.mb-0 Nivel de severidad      
            tbody.text-center
              tr
                td.fila-blue.text-white Servidor Web
                td.fila-amarillo2 5
                td.fila-amarillo2 4   
                td.fila-amarillo2 5  
                td.fila-amarillo2 
                  strong 100  
                td.fila-amarillo1 X 
                td.fila-amarillo1 3 
                td.fila-amarillo1 4 
                td.fila-amarillo1 
                  strong 60
                td.fila-amarillo1 
                  strong Moderado
              tr
                td.fila-blue.text-white Información Documental
                td.fila-amarillo2 5
                td.fila-amarillo2 4   
                td.fila-amarillo2 3  
                td.fila-amarillo2 
                  strong 60  
                td.fila-amarillo1 X 
                td.fila-amarillo1 4 
                td.fila-amarillo1 2 
                td.fila-amarillo1 
                  strong 40
                td.fila-amarillo1 
                  strong Moderado 
              tr
                td.fila-blue.text-white ...
                td.fila-amarillo2 ...
                td.fila-amarillo2 ...   
                td.fila-amarillo2 ...  
                td.fila-amarillo2 
                  strong ...  
                td.fila-amarillo1 ... 
                td.fila-amarillo1 ...
                td.fila-amarillo1 ... 
                td.fila-amarillo1 
                  strong ...
                td.fila-amarillo1 
                  strong ...          

    Separador
    
    #t_8_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      .h2 8.2  Plan de tratamiento de riesgos

    .topSquare02.clr--pink.mb-5(data-aos="zoom-in")
      .row
        .col-lg-2.col-auto
          figure
            img(src='@/assets/curso/temas/t8/t8_03.png', alt='imagen decorativa').img75.m-auto  
        .col
          p Una vez se tenga la matriz de riesgos se debe desarrollar un plan de tratamiento de riesgos #[strong PTR]. En ciberseguridad, consiste en una serie de actividades a desarrollar, en función de riesgos de ciberseguridad no aceptables, severos o críticos, resultantes del proceso de análisis de riesgos; tales actividades buscan fortalecer, corregir o implementar controles de ciberseguridad para la reducción de riesgos asociados a los activos de información.   
          

    .row.justify-content-center(data-aos="zoom-in")
      .col-md-10
        .bg--paleYellow.br_cstm.p-4
          .row
            .col-lg-7.mb-0.px-md-4.py-md-0.px-3.py-5
              p El plan de tratamiento de riesgos se debe construir considerando los siguientes aspectos:
              ul.lista-ul--color.lista-acento-botones
                li.mb-0 
                  i.fas.fa-square
                  | Activo de Información con riesgos críticos.
                li.mb-0 
                  i.fas.fa-square
                  | Riesgos residuales asociados.
                li.mb-0 
                  i.fas.fa-square
                  | Causas de riesgo asociadas.
                li.mb-0 
                  i.fas.fa-square
                  | Controles asociados a los riesgos. 
                li.mb-0 
                  i.fas.fa-square
                  | Tipo de tratamiento; mitigar o reducir el riesgo, evitar el riesgo, compartir o transferir el riesgo.
                li.mb-0 
                  i.fas.fa-square
                  | Actividades a realizar. 
                li.mb-0 
                  i.fas.fa-square
                  | Responsable. 
                li.mb-0 
                  i.fas.fa-square
                  | Prioridad.  
                li.mb-0 
                  i.fas.fa-square
                  | Fecha de Implementación de las actividades.
                li.mb-0
                  i.fas.fa-square
                  | Observaciones.                    
            .col-lg-5.mb-4.mb-md-0.px-md-4(data-aos="fade-left")
              figure.mb-4
                img(src='@/assets/curso/temas/t8/t8_04.png', alt='imagen decorativa')  
              .row
                .col-6
                  a.boton.color-acento-botones.indicador__container.text-center.modal-centrado(@click="modal1 = true")
                    span Ver más
                    i.fas.fa-chevron-right
                    .indicador--click(v-if="mostrarIndicador")  
                  .row.justify-content-center.align-items-center
                    .col-md-5
                    
                      ModalA.modal-borde(:abrir-modal.sync="modal1")
                        .row.justify-content-center.align-items-center
                          .col-auto.mb-4.mb-lg-0
                            figure
                              img(src='@/assets/curso/temas/t8/t8_05.svg', alt='imagen decorativa').img75.m-auto
                          .col-lg
                            p.text-white.mb-0 Una vez se haya realizado el Plan de Tratamiento de Riesgos se debe comunicar a las partes interesadas, principalmente a los responsables de los activos de información y se debe dejar un registro de aceptación del plan de tratamiento de riesgos.
                .col-6
                  a.boton.color-acento-botones.indicador__container.text-center.modal-centrado(@click="modal2 = true")
                    span Ver más
                    i.fas.fa-chevron-right
                    .indicador--click(v-if="mostrarIndicador")  

                  ModalA.modal-borde(:abrir-modal.sync="modal2")
                    .row.justify-content-center.align-items-center
                      .col-auto.mb-4.mb-lg-0
                        figure
                          img(src='@/assets/curso/temas/t8/t8_06.svg', alt='imagen decorativa').img75.m-auto
                      .col-lg
                        p.text-white.mb-0 El 
                          strong PTR
                          | , plan de tratamiento de riesgos, debe ser revisado periódicamente para determinar la conformidad, según las fechas de implementación de las actividades.

</template>

<script>
export default {
  name: 'Tema8',
  data: () => ({
    // variables de vue
    modal1: false,
    modal2: false,
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
