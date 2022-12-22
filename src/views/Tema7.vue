<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 7
      h1 Valoración

    .row.justify-content-center
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-left")
        p La valoración de riesgos es un proceso que inicia con la valuación de los activos de información, luego pasa por la valoración de la probabilidad de ocurrencia de riesgos asociados a los activos y termina con la valoración del impacto.
        p.fondo-rojo.mb-0.p-4 En términos generales el riesgo es igual a la probabilidad por impacto; 
          span.etiqueta Riesgo = Probabilidad x Impacto. 
          | Pero en ciberseguridad el impacto está determinado por el valor del activo de información por el impacto general de las dimensiones de impacto organizacionales. 
      .col-lg-5.col-10(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/t7/t7_01.png', alt='imagen decorativa')   

    Separador
    
    #t_7_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.1 Riesgo inherente

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-md-10.fondo-rosado
        .row.align-items-center.justify-content-center.py-md-4.p-4
          .col-auto.mb-4.mb-lg-0
            img.px-md-3(src='@/assets/curso/temas/t7/t7_02.svg', alt='imagen decorativa') 
          .col-lg
            p.mb-0 Consiste en el riesgo valorado antes de que se le haya aplicado un tratamiento o controles para su mitigación. También es denominado riesgo potencial.

    p.mb-4(data-aos="fade-left") Sobre el riesgo inherente, se debe tener en cuenta:

    .row.justify-content-center.mb-4
      .col-md-10
        .row.justify-content-center.mb-5
          .col-md-6.mb-4.mb-lg-0(data-aos="flip-left")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t7/t7_03.svg' alt='AvatarTop')
              .tarjeta.color-acento-contenido.bg--piel
                .p-4
                  h3.text-center Proceso temprano
                  p Es importante que se determine este tipo de riesgo inicialmente para poder luego aplicar los controles de ciberseguridad y determinar el riesgo residual, logrando entender que controles son necesarios de fortalecer, cambiar o implementar.
          .col-md-6(data-aos="flip-left")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t7/t7_04.svg' alt='AvatarTop')
              .tarjeta.color-acento-contenido.bg--sandia
                .p-4
                  h3.text-center Escala de evaluación
                  p La escala de evaluación de riesgos puede ser determinada como cada organización crea conveniente, y es importante que determine los niveles de aceptación y tratamiento de riesgos.       

    .row.justify-content-center(data-aos="zoom-in")
      .titulo-sexto.color-acento-botones
        p.mb-0
          strong Tabla 8. 
          |  Referencia de severidad del riesgo.
      .tabla-b.border-diferentes.tabla-2.color-primario.mb-2
        table  
          thead.tabla-b__header 
            tr
              th(colspan="6")  
                h4.text-white.mb-0 Severidad del riesgo
            tr
              th(style="width:5%;").rojo
                h5.text-white.mb-0 N°
              th(style="width:10%;").rojo
                h5.text-white.mb-0 VALOR
              th(style="width:55%;").rojo
                h5.text-white.mb-0 Descripción
              th(style="width:10%;").rojo
                h5.text-white.mb-0 Acción    
              th(style="width:10%;").rojo
                h5.text-white.mb-0 Límite inferior 
              th(style="width:10%;").rojo
                h5.text-white.mb-0 Límite superior     
          tbody
            tr.fila-amarillo1
              td.text-center 1
              td.text-center Severo
              td El nivel del riesgo es Inadmisible o severo, por lo que es necesario implementar controles en la Organización para mitigar, evitar o compartir el riesgo y llevar el mismo a niveles aceptables.
              td.text-center Evitar / Reducir / Transferir
              td.text-center 70
              td.text-center 125
            tr.fila-blanco
              td.text-center 2
              td.text-center Moderado
              td El nivel de riesgo es Tolerable o moderado de acuerdo a los criterios de aceptación de la Organización. Los riesgos en esté nivel deben ser monitoreados para identificar oportunamente los cambios en su valoración.
              td.text-center Aceptar / Monitorear
              td.text-center 20
              td.text-center 69  
            tr.fila-amarillo1
              td.text-center 3
              td.text-center Leve
              td El nivel de riesgo es Aceptable y se encuentra controlado en la Organización o el mismo es insignificante. Los riesgos en esté nivel se deben revisar periódicamente.
              td.text-center Aceptar
              td.text-center 1
              td.text-center 19  

    Separador
    
    #t_7_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.2  Evaluación de controles de seguridad

    p(data-aos="fade-left").mb-4 La evaluación de controles es un aspecto importante dentro del análisis de riesgos, para ello se deben inventariar los controles existentes y realizar la evaluación, conforme a los detalles de referencia.

    .row.justify-content-center.mb-4
      .col-lg-5.col-8.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/t7/t7_05.png', alt='imagen decorativa')  

      .col-lg-7.px-md-5.py-md-3.p-4(data-aos="fade-left")
        .bg--piel.br_cstm.p-4
          p El inventario de controles se debe realizar siguiendo la siguiente estructura:
          ul.lista-ul--color.lista-acento-botones.mb-0
            li.mb-0 
              i.fas.fa-square
              | Número de control.
            li.mb-0 
              i.fas.fa-square
              | Nombre del control.
            li.mb-0 
              i.fas.fa-square
              | Descripción del control.
            li.mb-0 
              i.fas.fa-square
              | Asignación del control.
            li.mb-0 
              i.fas.fa-square
              | Tipo de control: preventivo, correctivo.
            li.mb-0 
              i.fas.fa-square
              | Naturaleza del control.
            li.mb-0 
              i.fas.fa-square
              | Frecuencia.
            li.mb-0 
              i.fas.fa-square
              | Evidencia/Documentación.
            li.mb-0 
              i.fas.fa-square
              | Funcionalidad.  

    p(data-aos="fade-left").mb-4 Se debe conocer la referencia de evaluación de controles que el siguiente recurso tiene. Allí mismo, se debe ampliar el conocimiento en la determinación de diseños de control y ejecución de los controles.#[strong ¡Adelante!]

    .row.mb-4(data-aos="zoom-in")
      .titulo-numero-acento-botones 
        .fondo-1-acento-botones
          h3.mb-0 1
      .row.bloque-borde-acento-botones.p-4.py-3
        p.mt-4 Para comenzar, analice y comprenda esta tabla de referencia para la evaluación de controles.
        .tabla-b.tabla-3.color-primario.border-diferentes.mb-2
          table  
            thead.tabla-b__header 
              tr
                th(colspan="13")  
                  h4.text-white.mb-0 Elementos para la evaluación del diseño de controles
              tr
                th.rojo
                  h5.text-white.mb-0 Asignación
                th.rojo
                  h5.text-white.mb-0 Valor
                th.rojo
                  h5.text-white.mb-0 Tipo
                th.rojo
                  h5.text-white.mb-0 Valor    
                th.rojo
                  h5.text-white.mb-0 Naturaleza 
                th.rojo
                  h5.text-white.mb-0 Valor  
                th.rojo
                  h5.text-white.mb-0 Frecuencia 
                th.rojo
                  h5.text-white.mb-0 Valor 
                th.rojo
                  h5.text-white.mb-0 Documentación 
                th.rojo
                  h5.text-white.mb-0 Valor  
                th.rojo
                  h5.text-white.mb-0 Evidencia / Soporte 
                th.rojo
                  h5.text-white.mb-0 Funcionalidad 
                th.rojo
                  h5.text-white.mb-0 Valor                 
            tbody
              tr.text-center.fila-amarillo1
                td Asignado
                td 30%
                td Preventivo
                td 10%
                td Automático
                td 20%
                td Adecuada
                td 10%
                td Documentado
                td 10%
                td Actas de comité o actas de reuniones
                td Adecuada
                td 20%
              tr.text-center.fila-blanco
                td No Asignado
                td 0%
                td Detectivo
                td 7%
                td Desarrollo de TI
                td 7%
                td Inadecuada
                td 0%
                td No documentado
                td 0%
                td Archivos digitales 
                td Inadecuada
                td 0%  
              tr.text-center.fila-amarillo1
                td - -
                td - -
                td Correctivo
                td 5%
                td Manual
                td 5%
                td - -
                td - -
                td - -
                td - -
                td Correos corporativos
                td - -
                td - -
              tr.text-center.fila-blanco
                td - -
                td - -
                td - -
                td 0%
                td - -
                td 0%
                td - -
                td - -
                td - -
                td - -
                td Check list
                td - -
                td - -  
              tr.text-center.fila-amarillo1
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Formatos
                td - -
                td - -    
              tr.text-center.fila-blanco
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Informes de gestión
                td - -
                td - -  
              tr.text-center.fila-amarillo1
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Políticas organizacionales - procedimientos
                td - -
                td - -  
              tr.text-center.fila-blanco
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Registros financieros
                td - -
                td - -  
              tr.text-center.fila-amarillo1
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Registros administrativos
                td - -
                td - -
              tr.text-center.fila-blanco
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Registros operativos
                td - -
                td - -
              tr.text-center.fila-amarillo1
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td - -
                td Registros digitales
                td - -
                td - -            
        figcaption Nota. Tomado de Modelo MSPI. MinTic. (2016).

    .row.justify-content-between(data-aos="zoom-in")
      .col-md-6.cajas-numeros
        .row.mb-4
          .titulo-numero-acento-contenido 
            .fondo-1-acento-contenido
              h3.mb-0 2
          .row.bloque-borde-acento-contenido.justify-content-center.align-items-center.py-3
            .col-md-4.col-6.mt-3
              img(src='@/assets/curso/temas/t7/t7_05A.svg', alt='imagen decorativa')  
            .col-md-8.mt-3
              p.mb-0 Una vez inventariados y evaluados los controles, se debe determinar el diseño del control, la ejecución, la solidez individual, la importancia del control y la solidez del conjunto del control.

      .col-md-6.cajas-numeros
        .row.mb-4
          .titulo-numero-acento-botones 
            .fondo-1-acento-botones
              h3.mb-0 3
          .row.bloque-borde-acento-botones.justify-content-center.align-items-center.py-3
            .col-md-4.col-6.mt-3
              img(src='@/assets/curso/temas/t7/t7_05B.svg', alt='imagen decorativa')  
            .col-md-8.mt-3
              p.mb-0 El Diseño del control es la sumatoria de la 
                italic-strong Asignación del control con el Tipo de control (Preventivo, Correctivo) + la  Naturaleza del control, la Frecuencia y la Funcionalidad.
    
    .row.mb-4(data-aos="zoom-in")
      .titulo-numero-acento-contenido 
        .fondo-1-acento-contenido
          h3.mb-0 4
      .row.bloque-borde-acento-contenido.p-4.py-3
        p.mt-4 Analice, ahora, esta tabla referencia para determinar la ejecución, solidez e importancia de controles.
        .tabla-b.tabla-3.color-primario.mb-2
          table  
            thead.tabla-b__header 
              tr
                th(colspan="11")  
                  h4.text-white.mb-0 Ejecución, solidez e importancia del control
              tr
                th.rojo
                  h5.text-white.mb-0 N°
                th.rojo
                  h5.text-white.mb-0 Ejecución
                th.rojo
                  h5.text-white.mb-0 Descripción
                th.rojo
                  h5.text-white.mb-0 Valor    
                th.rojo
                  h5.text-white.mb-0 Solidez 
                th.rojo
                  h5.text-white.mb-0 Valor  
                th.rojo
                  h5.text-white.mb-0 Límite inferior 
                th.rojo
                  h5.text-white.mb-0 Límite superior 
                th.rojo
                  h5.text-white.mb-0 Importancia 
                th.rojo
                  h5.text-white.mb-0 Descripción  
                th.rojo
                  h5.text-white.mb-0 Valor                
            tbody
              tr.text-center.fila-amarillo2
                td.gris-3 1
                td Fuerte
                td Control que se ejecuta cada vez que se desarrolla la actividad.
                td 5
                td Fuerte
                td 5
                td 16
                td 25
                td Muy Importante
                td Si el control garantiza cero errores.
                td 5
              tr.text-center
                td.gris-3 2
                td Moderado
                td Control que se aplica en momentos determinados.
                td 3
                td Moderado
                td 3
                td 9
                td 15
                td Importante
                td Si el control garantiza un buen desempeño.
                td 3  
              tr.text-center.fila-amarillo2
                td.gris-3 3
                td Débil
                td Control que se efectúa cuando se requiere.
                td 1
                td Débil
                td 1
                td 1
                td 5
                td Poco Importante
                td Si lo que aporta el control no es significativo.
                td 1
        figcaption Nota. Tomado de Modelo MSPI. MinTic. (2016).

    .row.justify-content-between(data-aos="zoom-in")
      .col-md-6.cajas-numeros
        .row.mb-4
          .titulo-numero-acento-botones 
            .fondo-1-acento-botones
              h3.mb-0 5
          .row.bloque-borde-acento-botones.justify-content-center.align-items-center.py-3
            .col-md-4.col-6.mt-3
              img(src='@/assets/curso/temas/t7/t7_06.svg', alt='imagen decorativa')  
            .col-md-8.mt-3
              p.mb-0 La ejecución del control se determina manualmente, mientras que la 
                strong Solidez individual 
                | será igual al 
                strong diseño del control 
                | por la ejecución del control.
      .col-md-6.cajas-numeros
        .row.mb-4
          .titulo-numero-acento-contenido 
            .fondo-1-acento-contenido
              h3.mb-0 6
          .row.bloque-borde-acento-contenido.justify-content-center.align-items-center.py-3
            .col-md-4.col-6.mt-3
              img(src='@/assets/curso/temas/t7/t7_07.svg', alt='imagen decorativa')  
            .col-md-8.mt-3
              p.mb-0 Así entonces: 
              p Solidez individual del control
              p.mb-0.resaltado-caja.py-2.px-4
                strong Si = Diseño del control X Ejecución del control

    Separador
   
    #t_7_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.3 La importancia del control

    p.mb-4(data-aos="fade-left") La Importancia del control se determina manualmente; habiéndola determinado es más sencillo determinar la solidez del conjunto de control, que es el resultado que ayudará a determinar si el control puede, o no, disminuir un riesgo. La solidez del conjunto de control es igual a la solidez individual del control más la Importancia, sobre tres (3).
    
     .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10.fondo-rosado
        .row.align-items-center.justify-content-center.py-md-4.p-4
          .col-auto.mb-4.mb-lg-0
            img.px-md-3(src='@/assets/curso/temas/t7/t7_08.svg', alt='imagen decorativa').img190
          .col-md-8
           h5 Solidez del conjunto de control, Sc = (solidez individual del control + Importancia) / 3

    p.mb-4(data-aos="fade-left") Se debe tener muy presente los aspectos que se muestran en el siguiente recurso, sobre la importancia del control y la solidez del conjunto de controles; no olvidar la toma de nota sobre ellos:

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in")
      .row.justify-content-center(titulo="División sobre tres")
        .col-lg-9
          p Se divide sobre tres (3) teniendo en cuenta los valores de referencia que se han utilizado.
        .col-lg-3.col-8
          img.px-md-4(src="@/assets/curso/temas/t7/t7_09.svg", alt="División sobre tres")

      .row.justify-content-center(titulo="Coherencia con la realidad")
        .col-lg-9
          p Es importante que en cada método de valoración o medición establecido en la organización se determine que, el mismo, sea coherente y pueda representar lo mejor posible la realidad.
        .col-lg-3.col-8
          img.px-md-4(src="@/assets/curso/temas/t7/t7_10.svg", alt="Coherencia con la realidad") 

      .row.justify-content-center(titulo="Referencia")
        .col-lg-12
          p Esta es la referencia para determinar la solidez del conjunto de controles:
          .titulo-sexto.color-acento-contenido
            p.mb-0
              strong Tabla 10. 
              | Referencia para determinarla solidez del conjunto de controles
          .tabla-b.tabla-2.color-primario.border-diferentes.mb-2
            table  
              thead.tabla-b__header 
                tr
                  th(colspan="7")  
                    h4.text-white.mb-0 Solidez del conjunto de controles
                tr
                  th.rojo
                    h5.text-white.mb-0 Calificación
                  th.rojo
                    h5.text-white.mb-0 ES
                  th.rojo(colspan="2")
                    h5.text-white.mb-0 Valor
                  th.rojo
                    h5.text-white.mb-0 Límite inferior    
                  th.rojo
                    h5.text-white.mb-0 Límite superior
                  th.rojo
                    h5.text-white.mb-0 Disminución de la probabilidad e/o impacto     
              tbody
                tr.fila-amarillo1.text-center
                  td Fuerte
                  td >=
                  td(colspan="2") 3.3
                  td 3.3
                  td 5
                  td 2
                tr.fila-blanco.text-center
                  td Moderado
                  td >= Y <
                  td 2.5
                  td 3.2
                  td 2.5
                  td 3.2
                  td 1 
                tr.fila-amarillo1.text-center
                  td Débil
                  td <
                  td(colspan="2") 2.5
                  td 0
                  td 2.4
                  td 0  
          figcaption Nota. Tomado de Modelo MSPI. MinTic. (2016).  

      .row.justify-content-center(titulo="Solidez del conjunto de controles")
        .col-lg-9
          p Cuando se aplican varios controles en el tratamiento de un riesgo, el promedio de la Solidez del conjunto de control de los controles aplicados, determina la Solidez del conjunto de controles para la disminución de la probabilidad e/o impacto.
        .col-lg-3.col-8
          img.px-md-4(src="@/assets/curso/temas/t7/t7_11.svg", alt="Solidez del conjunto de controles")

      .row.justify-content-center(titulo="Aplicación de controles a riesgos")
        .col-lg-12
          .titulo-sexto.color-acento-contenido
            p.mb-0
              strong Tabla 11. 
              | Referencia de aplicación de controles a riesgos
          .tabla-b.tabla-2.color-primario.border-diferentes.mb-2
            table  
              thead.tabla-b__header 
                tr
                  th.rojo
                    h5.text-white.mb-0 Riesgo
                  th.rojo
                    h5.text-white.mb-0 Sc. Control 1
                  th.rojo
                    h5.text-white.mb-0 Sc. Control 2
                  th.rojo
                    h5.text-white.mb-0 Sc. Control 3    
                  th.rojo
                    h5.text-white.mb-0 Sc. Control n
                  th.rojo
                    h5.text-white.mb-0 Promedio Sc. controles  
                  th.rojo
                    h5.text-white.mb-0 Disminuye probabilidad
                  th.rojo
                    h5.text-white.mb-0 Disminuye impacto      
              tbody
                tr.fila-amarillo1.text-center
                  td Riesgo 1
                  td NA
                  td 3.3
                  td 2.7
                  td ...
                  td 3
                  td 1
                  td 1
                tr.fila-blanco.text-center
                  td Riesgo 2
                  td 1
                  td 3.3
                  td 2.7
                  td ...
                  td 2.33
                  td 0
                  td 0          
        

    Separador
    
    #t_7_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.4 Riesgo residual
    
    .topSquare02.clr--pink.mb-5(data-aos="zoom-in")
      .row
        .col-lg-2.col-auto
          figure
            img(src="@/assets/curso/temas/t7/t7_12.svg", alt="alt").img75.m-auto
        .col
          p El riesgo residual, consiste en el riesgo repercutido o resultante, después de que se aplican controles o medidas para la reducción de los mismos.
          p.mb-0 Se debe prestar atención a los siguientes aspectos a tener en cuenta en lo referente al riesgo residual:      

    .row.justify-content-center.mb-4
      .col-md-10
        .row
          .col-md-6.mb-lg-0(data-aos="flip-right")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t7/t7_13.svg' alt='AvatarTop')
              .tarjeta.color-acento-contenido.bg--piel
                .p-4
                  h3.text-center Su determinación
                  p.text-center La determinación del riesgo residual se realiza a partir de que un control disminuye la probabilidad o impacto de un riesgo.
          .col-md-6.mb-lg-0(data-aos="flip-left")
            .tarjeta-avatar
              img(src='@/assets/curso/temas/t7/t7_14.svg' alt='AvatarTop')
              .tarjeta.color-acento-contenido.bg--sandia
                .p-4
                  h3.text-center ¿Qué debe haberse hecho?
                  p.text-center Para determinar riesgos, es importante que se haya realizado un adecuado inventario, evaluación de controles y aplicación de los mismos a los riesgos del catálogo de riesgos, según corresponda.
                  p.text-center Una vez que se tengan los riesgos residuales se deben aplicar actividades de tratamiento para aquellos que como resultado, dieron críticos, altos o muy altos, según se considere.

</template>

<script>
export default {
  name: 'Tema7',
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
