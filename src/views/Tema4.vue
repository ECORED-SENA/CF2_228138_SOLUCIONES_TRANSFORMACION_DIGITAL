<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 4
      h1 Herramientas de análisis de seguridad digital

    .row.justify-content-center(data-aos="zoom-in")
      .col-md-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-4.mb-4
          .bloque-texto-g__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t4/t4_01.png')})`}")
          .bloque-texto-g__texto.py-5.px-4            
            p.mb-0 Dentro de los controles de seguridad digital existen diversas herramientas para el análisis de la seguridad digital, las mismas permiten realizar diagnósticos del estado de la seguridad en los componentes de infraestructura de <em>hardware</em> y <em>software</em>.
            

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-md-10
        .bg--pink.p-4
          .row.justify-content-center.align-items-end
            .col-lg-6.mb-4.mb-lg-0
              ul.fa-ul
                li.mb-0 
                  i.fa-li.fas.fa-play.clr--darkBlue
                  | Algunas herramientas básicas, muy comunes, para realizar análisis de seguridad digital son:            

              ul.fa-ul.ms-5
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em Nmap (“mapeador de redes”)].
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em Wireshark.]
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em OpenVAS]
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em OWA SP Zen Attack Proxy – ZAP.] 
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em Nessus.]
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em Vega.]
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  | #[em Mesploit Framework.] 
                    
              ul.fa-ul
                li.mb-0 
                  i.fa-li.fas.fa-play.clr--darkBlue
                  | También existen sistemas operativos enfocados a seguridad de digital:

              ul.fa-ul.ms-5
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  |#[em Kali Linux OS.]
                li.mb-0 
                  i.fa-li.fas.fa-square.clr--prime
                  |#[em Parrot OS.] 

            .col-lg-6.col-8
              figure
                img(src='@/assets/curso/temas/t4/t4_02.svg', alt='imagen decorativa')  

    p.mb-4(data-aos="fade-left") Para profundizar en este punto se debe explorar el siguiente recurso didáctico:          

    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="zoom-in")
      .row.justify-content-center(titulo="Nmap (“mapeador de redes”)")
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_03.png', alt='Nmap (“mapeador de redes”)')
          figcaption.naranja Nota. Tomado de https://acortar.link/nZi8tH  
        .col-lg
          p “Es una herramienta de código abierto para exploración de red y auditoría de seguridad. Se diseñó para analizar rápidamente grandes redes, aunque funciona muy bien contra equipos individuales. 
            strong Nmap 
            | utiliza paquetes IP “crudos” («raw», N. del T.) en formas originales para determinar qué equipos se encuentran disponibles en una red, qué servicios (nombre y versión de la aplicación) ofrecen, qué sistemas operativos (y sus versiones) ejecutan, qué tipo de filtros de paquetes o cortafuegos se están utilizando, así como docenas de otras características. Aunque generalmente se utiliza 
            strong Nmap 
            | en auditorías de seguridad, muchos administradores de redes y sistemas lo encuentran útil para realizar tareas rutinarias, como puede ser el inventariado de la red, la planificación de actualización de servicios y la monitorización del tiempo que los equipos o servicios se mantiene activos.” Nmap.org (2021).

      .row.justify-content-center(titulo="<em>Wireshark</em>")
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_04.png', alt='WireShark')
          figcaption.naranja Nota. Tomado de https://acortar.link/OtEpu8 
        .col-lg
          p “Analizador de protocolos de red más importante y más utilizado del mundo. Le permite ver lo que está sucediendo en su red a un nivel microscópico y es el estándar de facto (y a menudo de jure) en muchas empresas comerciales y sin fines de lucro, agencias gubernamentales e instituciones educativas. El desarrollo de #[em #[strong WireShark]] prospera gracias a las contribuciones voluntarias de expertos en redes de todo el mundo y es la continuación de un proyecto iniciado por Gerald Combs en 1998.” WireShark.org (2021).

      .row.justify-content-center(titulo="<em>OpenVAS</em>")
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_05.png', alt='OpenVAS')
          figcaption.naranja Nota. Tomado de https://acortar.link/P8p4Wj
        .col-lg
          p “Es un escáner de vulnerabilidades con todas las funciones. Sus capacidades incluyen pruebas autenticadas y no autenticadas, varios protocolos industriales y de Internet de alto y bajo nivel, ajuste del rendimiento para escaneos a gran escala y un poderoso lenguaje de programación interno para implementar cualquier tipo de prueba de vulnerabilidad.
          p El escáner obtiene las pruebas para detectar vulnerabilidades de un feed que tiene un largo historial y actualizaciones diarias”.OpenVas.org (2021).

      .row.justify-content-center(titulo="<em>OWASP Zen Attack Proxy – ZAP</em>")
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_06.png', alt='OWASP Zen Attack Proxy – ZAP')
          figcaption.naranja Nota. Tomado de https://acortar.link/zZcD5Y
        .col-lg
          p  Es un escáner de seguridad que permite descubrir vulnerabilidades en las aplicaciones #[em web]. “La Fundación OWASP ® trabaja para mejorar la seguridad del #[em software] a través de sus proyectos de #[em software] de código abierto, liderados por la comunidad, cientos de capítulos en todo el mundo, decenas de miles de miembros y organizando conferencias locales y globales.”  Owasp.org (2021).

      .row.justify-content-center(titulo="<em>Nessus</em>")
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_07.png', alt='Nessus')
          figcaption.naranja Nota. Tomado de https://acortar.link/j7p45Y
        .col-lg
          p “Es un escáner de vulnerabilidades con el cual se pueden realizar evaluaciones de seguridad profundas y de alta velocidad, tiene soporte a través de #[em Tenable Community], y es ideal para educadores, estudiantes e individuos que inician sus carreras en ciberseguridad”.  Basado en tenable.com (2021).   

      .row.justify-content-center(titulo="<em>Vega</em>")       
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_08.png', alt='Vega')
          figcaption.naranja Nota. Tomado de https://acortar.link/5qALCU
        .col-lg
          p "Es un escáner de seguridad web gratuito y de código abierto y una plataforma de prueba de seguridad web para probar la seguridad de las aplicaciones #[em web]. #[em #[strong Vega]] puede ayudarlo a encontrar y validar #[em SQL Injection, Cross-Site Scripting] (XSS), información confidencial divulgada inadvertidamente y otras vulnerabilidades. Está escrito en Java, basado en GUI y se ejecuta en Linux, OS X, Windows." Subgraph.com/vega (2021).           

      .row.justify-content-center(titulo="<em>Metasploit Framework</em>")
        .col-lg-4.col-8.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/temas/t4/t4_09.png', alt='Metasploit Framework')
          figcaption.naranja Nota. Tomado de https://acortar.link/Yvm4xz
        .col-lg
          p “El #[em Metasploit Framework] (MSF) es mucho más que una simple colección de #[em exploits], sino que también es una base sólida que se puede aprovechar y personalizar fácilmente para satisfacer sus necesidades. Esto le permite concentrarse en su entorno objetivo único y no tener que reinventar la rueda. Consideramos que MSF es una de las herramientas de auditoría de seguridad más útiles disponibles gratuitamente para los profesionales de la seguridad en la actualidad. Desde una amplia gama de #[em exploits] de grado comercial y un amplio entorno de desarrollo de #[em exploits], hasta herramientas de recopilación de información de red y complementos de vulnerabilidad web. #[em Metasploit Framework] proporciona un entorno de trabajo realmente impresionante.” #[em Offensive-Security.com] (2021).                   

    p(data-aos="fade-left").mb-4 También existen sistemas operativos enfocados a seguridad digital, los cuales contienen una serie de herramientas de seguridad informática para las revisiones de ciberseguridad, entre los más populares están:

    .tarjeta--container.row.mb-5
      .col-md.bg--sandia.br_01.p-md-5.p-4.mb-4.mb-lg-0(data-aos="flip-left")
        .row.justify-content-center.mb-4
          .col-8
            figure
              img.px-md-1(src='@/assets/curso/temas/t4/t4_10.svg', alt='Kali Linux OS')
        h3.text-center Kali Linux OS
        p.text-center Es un sistema operativo GNU/Linux basado en Debian. Contiene preconfiguradas, diversas herramientas #[em software]  para realizar pruebas de seguridad. “La plataforma de pruebas de penetración de Kali Linux contiene una amplia gama de herramientas y utilidades. Desde la recopilación de información hasta los informes finales, Kali Linux permite a los profesionales de la seguridad y de TI evaluar la seguridad de sus sistemas”. Kali.org (2021)

      .col-md.bg--piel.br_01.p-md-5.p-4(data-aos="flip-left")
        .row.justify-content-center.text-white.mb-4
          .col-10
            figure
              img(src='@/assets/curso/temas/t4/t4_11.svg', alt='Parrot OS')
        h3.text-center Parrot OS
        p.text-center Es una distribución GNU / Linux basada en Debian y diseñada pensando en la seguridad y la privacidad. Incluye un laboratorio portátil completo para todo tipo de operaciones de seguridad cibernética, desde pentesting hasta análisis forense digital e ingeniería inversa, pero también incluye todo lo necesario para desarrollar su propio #[em software] o mantener sus datos seguros - Parrotsec.org (2021).

</template>

<script>
export default {
  name: 'Tema4',
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
