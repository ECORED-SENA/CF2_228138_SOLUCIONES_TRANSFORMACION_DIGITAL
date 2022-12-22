<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 9
      h1 Reglas de negocio

    p(data-aos="fade-left").mb-4 Describen las políticas, normas, definiciones, operaciones y restricciones presentes en una empresa, convirtiéndose en un elemento estratégico de importancia vital para cumplir con el modelo de negocio de la organización, por lo cual se hace necesario destacar que las empresas funcionan por las áreas clave y subdivisiones estratégicas, como  el departamento TI, compras, ventas, finanzas, gerencia, entre otras. 

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10
        .topSquare.clr--pink
          .row.justify-content-center.align-items-center
            .col-lg-3.col-auto.mb-4.mb-lg-0
              figure
                img(src="@/assets/curso/temas/t9/t9_01.svg", alt="alt").img265.m-auto
            .col-lg
              p Es por esto, que, al momento de dar el paso para la transformación digital en la organización, se debe partir del análisis de todos los procesos y cómo estos se relacionan entre sí, identificando complejidades y oportunidades de mejora que podrían ser abordadas con el apoyo tecnológico o la automatización.
              p.mb-0 A continuación, se presentan los aspectos clave para identificar las reglas de negocio.

    .bg--paleYellow.br_01.p-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Repetitiva
            p Se deben identificar cuáles son las decisiones que se repiten en el día a día de la organización, por ejemplo: aprobar o rechazar un requerimiento. 

          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t9/t9_02.png', alt='')

        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Objetividad
            p Son los parámetros que se identifican por medio del número de cédula o RUT (Registro Único Tributario), por ejemplo: para el sistema del banco al consultar la cédula, él prioriza el turno en caso de que sea cliente o una persona de la tercera edad. 

          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t9/t9_03.png', alt='')

        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Determinista
            p En este parámetro se determina al cliente preferencial ofreciéndole siempre los mejores descuentos antes los demás usuarios. Ejemplo: si al realizar un préstamo bancario, el cliente cuenta con buen manejo y es preferencial, siempre se le mantiene la tasa mínima de interés.   

          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t9/t9_04.png', alt='')

        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Operacional
            p Son las acciones clave que se ejecutan en el día a día de la organización, por ejemplo: importaciones, compras o ventas, entre otros.   

          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t9/t9_05.png', alt='')

        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            h3 Relevancia
            p Es necesario identificar las áreas y procesos implicados donde se toman decisiones, se definen políticas, directrices, procedimientos, por ejemplo: en aspectos de seguridad frente a la organización al detectar un riesgo, el jefe del departamento TI determina las acciones de tratamiento, pues sería el área competente para implementar la misma.  

          .col-lg-6
            figure
              img(src='@/assets/curso/temas/t9/t9_06.png', alt='')

    separador

    #t_9_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.1 Herramientas de automatización de procesos

    p(data-aos="fade-left").mb-4 Es la operacionalización de un proceso que, inicialmente, se ejecutaba de forma manual y que al aplicar cambios apoyados en las nuevas tecnologías de información y comunicaciones se pueden generar la integración de sistemas y datos. Esto es un paso importante en la gestión empresarial que permite dar pasos y transformaciones, generando competitividad, eficiencia y valor al cliente.

    .topSquare02.clr--pink.mb-5(data-aos="zoom-in")
      .row
        .col-lg-2.col-auto
          figure
            img(src="@/assets/curso/temas/t9/t9_07.svg", alt="alt").img75.m-auto
        .col
          p.mb-0 Dentro de las herramientas de automatización de procesos, es importante reconocer las características y aportes que tiene cada una en los proceso, actividades y transformación digital, a saber:

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
          .row.justify-content-center(titulo="TagUI")
            .col-auto.order-2.order-lg-1
              figure
                img(src='@/assets/curso/temas/t9/t9_08.svg', alt='').img85
              
            .col-lg.order-1.order-lg-2.mb-4.mb-lg-0
              p.mb-0 Permite la automatización de tareas repetitivas ejecutadas en páginas web o en el escritorio, de manera que el ordenador pueda realizarlas y agilizar el proceso, bajo una estructura y unas condiciones determinadas. Es fácil de configurar gracias a una extensión de Chrome que es capaz de grabar las acciones web o las acciones que no se ven del buscador.

          .row.justify-content-center(titulo="Robocop")
            .col-auto.order-2.order-lg-1
              figure
                img(src='@/assets/curso/temas/t9/t9_09.svg', alt='').img85
              
            .col-lg.order-1.order-lg-2.mb-4.mb-lg-0
              p.mb-0 Ayuda a la automatización de procesos repetitivos que se ejecutan de forma local o en la nube, es utilizada en instituciones como la policía en la operación de los drones, para control o seguimiento; también se pueden utilizar en el campo, por ejemplo, en los cultivos de maíz con ondas sonoras para espantar murciélagos de noche.

          .row.justify-content-center(titulo="Asana")
            .col-auto.order-2.order-lg-1
              figure
                img(src='@/assets/curso/temas/t9/t9_10.svg', alt='').img85
              
            .col-lg.order-1.order-lg-2.mb-4.mb-lg-0
              p.mb-0 Ofrece funciones para la gestión de proyectos, cuenta con una interfaz de usuario sencilla que fomenta el uso y la interacción, presenta plantillas prediseñadas, calendario de equipo compartido, informes, programador de tareas, priorización de tareas y automatización de tareas repetitivas.

          .row.justify-content-center(titulo="ProcessMaker")
            .col-auto.order-2.order-lg-1
              figure
                img(src='@/assets/curso/temas/t9/t9_11.svg', alt='').img85
              
            .col-lg.order-1.order-lg-2.mb-4.mb-lg-0
              p.mb-0 Es una plataforma inteligente para la automatización de procesos de negocio, mediante búsquedas filtradas, puede crear rápidamente gráficos e informes personalizados. Cuenta con un motor de #[em scripting] que soporta JavaScript, Java, C# y más, comprobando la sintaxis y la validación de errores de proceso.

          .row.justify-content-center(titulo="ActiveBatch")
            .col-auto.order-2.order-lg-1
              figure
                img(src='@/assets/curso/temas/t9/t9_12.svg', alt='').img85
              
            .col-lg.order-1.order-lg-2.mb-4.mb-lg-0
              p.mb-0 Es una plataforma diseñada para orquestar flujos de trabajo automatizados mediante eventos, admite colas de mensajes, #[em tweets], transferencia de archivos FTP, envío de correo electrónico, gestión de #[em tickets] automatizados, se puede integrar por medio de las API para conectarse a cualquier servicio, aplicación o servidor. 

    .row.justify-content-center(data-aos="fade-down")
      .col-md-10
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-4.mb-5
          .bloque-texto-g__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t9/t9_13.png')})`}")
          .bloque-texto-g__texto.py-5.px-4           
            p.mb-0 La automatización de procesos de negocios mediante el uso de tecnologías de automatización, permite a las organizaciones gestionar las tareas recurrentes, donde es posible reemplazar el trabajo manual, delegando esas tareas a una herramienta industrial o digital, permitiendo que los empleados sigan aportando en aspectos clave del negocio y no se desperdicie el tiempo en tareas repetitivas que se pueden automatizar.
    
    separador

    #t_9_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.2 <em>Workflow</em>

    p(data-aos="fade-left") Es un flujo de trabajo en el que se relaciona un conjunto de actividades de proceso el cual se debe completar en un determinado orden y, de esa manera, alcanzar un objetivo en la organización.

    p(data-aos="fade-left").mb-4 Cuenta con tres secuencias de control, que son:

    .row.justify-content-center.mb-5
      .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="flip-left")
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t9/t9_14A.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .pillTitle.mb-4
                h4 Planificación
              ul.fa-ul
                li
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Ideación y recopilación de la información.
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Recepción de las solicitudes.
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Priorización y asignación de recursos.
                 

      .col-lg-4.col-8.mb-4.mb-lg-0(data-aos="flip-left")
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t9/t9_16A.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .pillTitle.mb-4
                h4 Ejecución              
              ul.fa-ul
                li
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Desarrollo y revisión.
                li
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Seguimiento del progreso.
                  
      .col-lg-4.col-8(data-aos="flip-left")
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t9/t9_15A.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              .pillTitle.mb-4
                h4 Revisión              
              ul.fa-ul
                li
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Aprobación.
                li
                  i.fa-li.far.fa-dot-circle.clr--white
                  |  Emisión de informes.

    p(data-aos="fade-left").mb-4 La definición de los worflow permite la articulación de los flujos de trabajo, donde intervienen diferentes actores, cada uno con un rol específico que aportará al proceso acorde a las reglas definidas y un objetivo de negocio, permitiendo segregar las tareas, aportando control y orden y optimizando los procesos dentro de la organización.

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-lg-10
        .bg--pink.br_01.p-4
          .row.justify-content-center
            .col-lg-4.col-8
              figure
                img(src='@/assets/curso/temas/t9/t9_17.png', alt='')
            .col-lg-8
              p Estos flujos de trabajo se pueden automatizar mediante la implementación de herramientas que ayudan a controlar el flujo de trabajo en todos sus aspectos, obteniendo mejores resultados, pudiendo aplicarse en flujos de producción, operación, administrativos, proyectos o procedimientos que así lo requieran.
              p.mb-0 A continuación, se presenta un ejemplo de herramienta para control de worflows:

    .row.justify-content-center(data-aos="zoom-in")
      .col-md-10
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img.px-md-2(src="@/assets/curso/temas/t9/t9_18.svg").img75
            .col-lg
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Asana
                  p.mb-0 En el siguiente enlace podrás explorar la herramienta Asana en versión gratuita, con la cual podrás crear un proyecto que requiera flujos de trabajo, asignar tareas asociándoles estados y prioridades, asignar responsables, controlar por lista, tablero o cronograma, entre otros. Regístrate con la cuenta de estudiante.                   
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://asana.com/es" target="_blank")
                    span Enlace web
                    i.fas.fa-link 

    separador

    #t_9_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 9.3 Orquestación de procesos

    p(data-aos="fade-left").mb-4 Consiste en dirigir y coordinar las interacciones de las diferentes operaciones por medio de las respuestas para evaluar y solicitar el siguiente conjunto de operaciones. Las organizaciones pueden tener docenas, cientos o miles de automatizaciones en sus sistemas y cuando las mismas cooperan entre sí, la táctica a utilizar es la orquestación de procesos es la estrategia que rige su cumplimiento ordenada y eficiente.

    .topSquare02.clr--pink.mb-5(data-aos="zoom-in")
      .row
        .col-lg-2.col-auto
          figure
            img(src='@/assets/curso/temas/t9/t9_19.svg', alt='imagen decorativa').img75.m-auto  
        .col
          p La práctica de la orquestación enlaza eficazmente una sucesión de automatizaciones que trabajan en entornos dispares, operando como integrador y empleando automatizaciones estratégicas para mejorar los flujos de trabajo.
          p.mb-0 Los beneficios en la orquestación de procesos son:   

    SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in")
      .bg--paleYellow.p-4.br_01.hg-100
        .row.justify-content-center.mb-3          
          img(src='@/assets/curso/temas/t9/t9_20.png' alt='').mb-4        
          p.mb-0 Se eliminan tareas repetitivas, facilitando un proceso más fluido y de mayor valor.

      .bg--pink.p-4.br_01.hg-100
        .row.justify-content-center.mb-3          
          img(src='@/assets/curso/temas/t9/t9_21.png' alt='').mb-4        
          p.mb-0 Procesos operativos más rápidos y se eliminan los cuellos de botella.

      .bg--paleYellow.p-4.br_01.hg-100
        .row.justify-content-center.mb-3          
          img(src='@/assets/curso/temas/t9/t9_22.png' alt='').mb-4        
          p.mb-0 Mejora de la toma de decisiones y seguimiento del estado de los procesos en tiempo real.

      .bg--pink.p-4.br_01.hg-100
        .row.justify-content-center.mb-3          
          img(src='@/assets/curso/temas/t9/t9_23.png' alt='').mb-4        
          p.mb-0 Reduce el papeleo y los costos asociados, y se mejora la realización de las tareas al asignarlas al personal más idóneo en el flujo de trabajo.

      .bg--paleYellow.p-4.br_01.hg-100
        .row.justify-content-center.mb-3          
          img(src='@/assets/curso/temas/t9/t9_24.png' alt='').mb-4        
          p.mb-0 Se generan controles más efectivos, se crean recordatorios y alertas cuando las tareas están por caducar.

      .bg--pink.p-4.br_01.hg-100
        .row.justify-content-center.mb-3          
          img(src='@/assets/curso/temas/t9/t9_25.png' alt='').mb-4        
          p.mb-0 Se pueden automatizar procesos mediante la implementación de tecnologías integradoras.




              

</template>

<script>
export default {
  name: 'Tema9',
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
