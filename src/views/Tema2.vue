<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 2
      h1 Vulnerabilidades y amenazas

    p(data-aos="fade-left").mb-4 En la determinación de riesgos de ciberseguridad es importante comprender los conceptos de vulnerabilidad y amenaza, entendiendo que una o más amenazas pueden aprovechar una o más vulnerabilidades; generando riesgos en la confidencialidad, la integridad y la disponibilidad de la información, principios elementales de la seguridad de la información.      

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10        
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/t2/t2_01.svg', alt='Riesgos de ciberseguridad')

          .bg--white.br_01.shadow.p-3(x="41%" y="10.5%" numero="+")
            .h4.mb-2 Sistemas de información
            p.mb-0 Pueden tener vulnerabilidades aprovechables por amenazas, y están expuestos a riesgos de ciberseguridad.
          .bg--white.br_01.shadow.p-3(x="84%" y="58%" numero="+")
            .h4.mb-2 Amenazas
            p.mb-0 Las amenazas siempre está presentes y en constante evolución.
          .bg--white.br_01.shadow.p-3(x="28%" y="79%" numero="+")
            .h4.mb-2 Vulnerabiliades
            p.mb-0 Las amenazas aprovechan las vulnerabilidades presentes en los sistemas de información.  


    p(data-aos="fade-left").mb-4 Para ampliar los conocimientos en lo referente a amenazas y vulnerabilidades, se debe explorar el recurso que se propone a continuación:      

    figure(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/mHAdqq_7FXg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    Separador
    
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Valoración de amenazas y vulnerabilidades

    .topSquare02.clr--pink.mb-5(data-aos="fade-left")
      .row
        .col-lg-2.col-auto
          figure
            img(src="@/assets/curso/temas/t2/t2_02.svg", alt="alt").img75.m-auto
        .col
          p.mb-0 La valoración de amenazas y vulnerabilidades se puede realizar de manera conjunta, agrupando las mismas en riesgos de ciberseguridad y determinando la probabilidad de ocurrencia de dichos riesgos.    

    p(data-aos="fade-left").mb-4 A través de las siguientes variantes se puede hacer la valoración pertinente de las amenazas y vulnerabilidades:

    TabsC.color-acento-botones(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Probabilidad de ocurrencia")
        .row.justify-content-center
          .col-md-10
            h4 Probabilidad de ocurrencia
            p.mb-4 La valoración se puede dar de manera cualitativa y cuantitativa, por lo general se realiza de manera cualitativa definiendo escalas nominales con referencias numéricas que facilitan los cruces con otras características del análisis de riesgo de ciberseguridad, ver tabla 1.
          .col-md-9.mb-4
            .titulo-sexto.color-acento-contenido
              p.mb-0
                strong Tabla 1. 
                | Probabilidad de ocurrencia.
            .tabla-a.border-diferentes.mb-2
              table
                tbody.text-center
                  tr
                    td 
                      strong MA
                    td Muy alta
                    td Casi seguro
                    td 5
                  tr.fila-amarillo2
                    td 
                      strong A
                    td Alta
                    td Muy alto
                    td 4
                  tr
                    td 
                      strong M
                    td Media 
                    td Posible
                    td 3
                  tr.fila-amarillo2
                    td 
                      strong B
                    td Baja
                    td Poco probable
                    td 2
                  tr
                    td 
                      strong MB
                    td Muy baja
                    td Muy raro
                    td 1        
            figcaption Nota. Tomado de MAGERIT (2012).

      .py-3.py-md-4(titulo="Inventario de amenazas y vulnerabilidades")
        .row.justify-content-center
          .col-md-10
            h4 Inventario de amenazas y vulnerabilidades
            p.mb-4 Para poder valorar la probabilidad de vulnerabilidades y amenazas hay que condensarlas en riesgos, por medio de un inventario de amenazas y elementos vulnerables asociados. Una representación puede ser como se muestra en la siguiente tabla 2:
          .col-md-10.mb-4
            .titulo-sexto.color-acento-contenido
              p.mb-0
                strong Tabla 2. 
                | Inventario de amenazas y vulnerabilidades.
            .tabla-b.tabla-2.color-primario.border-diferentes.mb-2
              table  
                thead.tabla-b__header 
                  tr
                    th(rowspan="2") 
                      h4.text-white.mb-0 AMENAZA
                    th(rowspan="2")  
                      h4.text-white.mb-0 TIPO
                    th(colspan="3")  
                      h4.text-white.mb-0 Tipo de activos que afecta
                    th(colspan="3") 
                      h4.text-white.mb-0 Dimensiones que afecta
                    th(colspan="3") 
                      h4.text-white.mb-0 Elementos vulnerables asociados  
                  tr.rojo
                    th
                      h5.text-white.mb-0 SW
                    th
                      h5.text-white.mb-0 HW
                    th
                      h5.text-white.mb-0 ...
                    th
                      h5.text-white.mb-0 Confidencialidad
                    th
                      h5.text-white.mb-0 INTEGRIDAD      
                    th
                      h5.text-white.mb-0 DISPONIBILIDAD
                    th
                      h5.text-white.mb-0 HW
                    th
                      h5.text-white.mb-0 SW      
                    th
                      h5.text-white.mb-0 ...  
                tbody.text-center
                  tr
                    td Ataque cibernético
                    td Intencionado   
                    td X  
                    td na  
                    td ...  
                    td X 
                    td X 
                    td X 
                    td na
                    td X 
                    td ...
                  tr.fila-amarillo2
                    td ...
                    td ...   
                    td ...  
                    td ...  
                    td ...  
                    td ... 
                    td ... 
                    td ... 
                    td ...
                    td ... 
                    td ...  
            figcaption Nota. Tomado de MAGERIT (2012).

      .py-3.py-md-4(titulo="Valoración de riesgos")
        .row.justify-content-center
          .col-md-10
            h4 Valoración de riesgos
            p.mb-4 La evaluación de riesgos de ciberseguridad que agrupa amenazas y vulnerabilidades de activos de información se realiza considerando el contexto y el tipo de activo de información, así entonces se puede considerar la siguiente tabla 3 de valoración:
          .col-md-10.mb-4
            .titulo-sexto.color-acento-botones
              p.mb-0
                strong Tabla 3. 
                | Valoración de riesgos
            .tabla-b.tabla-2.color-primario.border-diferentes.mb-2
              table  
                thead.tabla-b__header 
                  tr
                    th(rowspan="2") 
                      h4.text-white.mb-0 Activo de información
                    th(rowspan="2")  
                      h4.text-white.mb-0 TIPO
                    th(colspan="2")  
                      h4.text-white.mb-0 Riesgo 1
                    th(colspan="2")  
                      h4.text-white.mb-0 Riesgo 2
                    th(colspan="2") 
                      h4.text-white.mb-0 Riesgo 3
                    th(colspan="2") 
                      h4.text-white.mb-0 Riesgo 4 
                  tr.rojo
                    th
                      h5.text-white.mb-0 Probabilidad
                    th
                      h5.text-white.mb-0 Valor
                    th
                      h5.text-white.mb-0 P
                    th
                      h5.text-white.mb-0 V
                    th
                      h5.text-white.mb-0 P
                    th
                      h5.text-white.mb-0 V
                    th
                      h5.text-white.mb-0 P
                    th
                      h5.text-white.mb-0 V    
                    
                tbody.text-center
                  tr
                    td Servidor Web
                    td Hardware    
                    td MA  
                    td 5  
                    td M  
                    td 3 
                    td A 
                    td 4
                    td ...
                    td ...
                  tr.fila-amarillo2
                    td Aplicación
                    td Software   
                    td A  
                    td 4  
                    td B  
                    td 2 
                    td M 
                    td 3 
                    td ...
                    td ... 
                  tr
                    td Internet
                    td Servicio    
                    td No Aplica  
                    td NA  
                    td A  
                    td 4 
                    td MB 
                    td 1
                    td ...
                    td ...  
            figcaption Nota. Tomado de MAGERIT (2012).   


    Separador
      
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Tratamiento de riesgos

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/t2/t2_03.png', alt='imagen decorativa')         

      .col-lg-7.mb-4(data-aos="fade-left")
        p.mb-0 El tratamiento de riesgos de ciberseguridad consiste en una serie de actividades en donde se aplican políticas y controles de seguridad digital a los riesgos críticos resultantes del proceso de análisis de riesgos. En un análisis de riesgos, se debe desarrollar un plan de tratamiento de riesgos #[strong PTR], en donde se especifiquen los activos de información con los riesgos más críticos y las actividades que se deben desarrollar para mitigar los riesgos.
        

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10
        .bg--pink.br_cstm.p-4
          .row.justify-content-center
            .col-lg-7.mb-0.px-md-4.py-md-0.py-5.px-3(data-aos="fade-right")
              p Las características que se deben considerar para realizar un plan de tratamiento de riesgos son:
              ul.lista-ul--color.lista-acento-botones
                li.mb-0 
                  i.fas.fa-square
                  | Activos de información con riesgos críticos.
                li.mb-0 
                  i.fas.fa-square
                  | Riesgos asociados al activo. 
                li.mb-0 
                  i.fas.fa-square
                  | Causas de los riesgos.  
                li.mb-0 
                  i.fas.fa-square
                  | Controles aplicados.  
                li.mb-0 
                  i.fas.fa-square
                  | Tipo de tratamiento que se debe dar: mitigar o reducir el riesgo, evitar el riesgo, compartir o transferir el riesgo.  
                li.mb-0 
                  i.fas.fa-square
                  | Actividades a realizar para tratar el riesgo.  
                li.mb-0 
                  i.fas.fa-square
                  | Responsable por cada actividad.  
                li.mb-0 
                  i.fas.fa-square
                  | Prioridad de ejecución.  
                li.mb-0 
                  i.fas.fa-square
                  | Fecha de implementación.  
                li.mb-0
                  i.fas.fa-square
                  | Observaciones. 

            .col-lg-5.col-8.mb-4.mb-md-0.px-md-4
              figure.mb-4
                img(src='@/assets/curso/temas/t2/t2_04.svg', alt='imagen decorativa') 

              .row.justify-content-center
                .col-auto
                  a.boton.color-acento-botones.indicador__container.text-center.modal-centrado(@click="modal1 = true")
                    span Ver más
                    i.fas.fa-chevron-right
                    .indicador--click(v-if="mostrarIndicador")  

              .row.justify-content-center
                .col-md-5
                  ModalA.bg--darkBlue(:abrir-modal.sync="modal1")
                    .row.justify-content-center.align-items-center
                      .col-auto.mb-4.mb-lg-0
                        figure
                          img(src='@/assets/curso/temas/t2/t2_05.svg', alt='imagen decorativa')
                      .col-lg
                        p.text-white.mb-0 Es importante destacar que para tratar un riesgo se debe implementar controles de ciberseguridad o fortalecer los existentes asociados al riesgo. Esto permite la mitigación del riesgo ya que los controles bien aplicados logran disminuir la probabilidad o impacto de los riesgos.

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    modal1: false,
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
