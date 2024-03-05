<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Realización de pruebas de #[em Software]

    .d-flex.flex-wrap.flex-lg-nowrap.align-items-center.fondo-color-sistema-i.p-4.mb-4
      figure.mb-4.mb-lg-0.position-relative.figura-deco-1(data-aos="fade-right")
        img.mx-auto(src="@/assets/curso/temas/2.png",style="max-width: 289px;")
      .p-4.p-lg-5.cont_1_1(data-aos="fade-left")
        p.mb-0 Para realizar las pruebas de #[em software], es necesario establecer qué tipos de pruebas serán requeridas por el producto. Esto se debe a que no es necesario utilizar todos los tipos de pruebas existentes, sino más bien aquellas que sean necesarias para cada caso específico. Por esta razón, es crucial que el QA o el líder de pruebas determine qué tipos de prueba se adaptan mejor al proyecto en evaluación. A continuación, se especifican y describen los tipos de pruebas que se pueden utilizar.
    
    Separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Tipos de pruebas

    p.mb-4 Las pruebas de #[em software] se pueden clasificar principalmente en dos categorías: pruebas funcionales y pruebas no funcionales. Considerando los diversos aspectos y componentes de un producto de #[em software], se requerirán distintos tipos de pruebas, como pruebas unitarias, pruebas de integración, pruebas de estrés, pruebas de rendimiento, pruebas de escalabilidad, entre otras. Cada uno de estos tipos de pruebas determina la calidad de la aplicación, desde el código fuente hasta la interacción y experiencia del usuario.

    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-secundario.p-3.mb-5.borde-8
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/curso/temas/3.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Pruebas y calidad de software
                  p.mb-0.text-small Les invitamos a explorar el video y  descubrir los diferentes tipos de pruebas y enriquecer su conocimiento en esta área clave del desarrollo de #[em software].
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=TLs-a1Cok-w" target="_blank")
                    span(style="color: #12263F") Abrir video
                    i.fas.fa-file-video(style="color: #12263F")

    p.mb-4 Algunos de los tipos de pruebas más comunes se describen en los siguientes puntos.

    .cont-titulo-decorativo.p-2.mt-5.mb-4
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Pruebas funcionales

    p.mb-5 Se realizan para verificar las características cruciales para el negocio, incluyendo la funcionalidad y la usabilidad del #[em software]. Estas pruebas aseguran que las funcionalidades y características del #[em software] funcionen y se comporten conforme a lo esperado, sin inconvenientes. Validan la aplicación completa de acuerdo con las especificaciones detalladas en el Documento de Requisitos del #[em Software] (SRS, por sus siglas en inglés). Dentro de este conjunto de pruebas se incluyen las pruebas unitarias, pruebas de regresión, pruebas de interfaz, entre otras.

    .row.justify-content-center.mb-5
      .col-lg-9
        .fondo-color-sistema-j.borde-20.p-4
          .row.align-items-center
            .col-md-6
              figure.mb-4.mb-lg-0
                img.mx-auto(src="@/assets/curso/temas/5.png",style="max-width: 474px;")
            .col-md-6
              p.mb-0 IBM (2021) plantea que estas pruebas se basan en la ejecución y revisión de las funciones y en su interoperabilidad con sistemas específicos, se llevan a cabo en todos los niveles de prueba, buscan evaluar cada una de las opciones con las que cuenta el paquete informático, principalmente en el comportamiento externo del producto o aplicativo, también se las identifica como de tipo caja negra.
    
    .row.justify-content-center
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          p.mb-0 #[b Figura 1.] Tipos de pruebas funcionales.
        .fondo-color-sistema-h.borde-20.p-4
          figure.mb-4.mb-lg-0
            img.mx-auto(src="@/assets/curso/temas/6.svg",style="max-width: 650px;",alt="El diagrama presenta un esquema de las Pruebas funcionales en el desarrollo de software, destacando su naturaleza cíclica e interconectada. Se detallan cinco tipos de pruebas: Prueba de interfaz de compatibilidad, Pruebas de aceptación (UAT), Pruebas de regresión, Prueba de interfaz de usuario (GUI), y Prueba de instalación. Cada una es crucial para asegurar diferentes aspectos de la funcionalidad del software, desde la compatibilidad hasta la satisfacción del usuario y la estabilidad después de actualizaciones o cambios")

    .cont-titulo-decorativo.p-2.mt-5.mb-4
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Pruebas unitarias 

    .row.align-items-center.mb-5
      .col-lg-8
        p.mb-4 Estas pruebas se centran en validar elementos como componentes, unidades o piezas de forma individual e independiente dentro de un producto de #[em software], siguiendo el principio del Ciclo de Vida del Desarrollo de #[em Software] (SDLC, por sus siglas en inglés). Cualquier bloque de código, ya sea un procedimiento, función, método, constructor, clase o módulo, puede ser considerado una unidad y, por lo tanto, debe ser objeto de pruebas unitarias. Esto permite determinar su comportamiento y validar si los resultados obtenidos se alinean con los esperados. Las pruebas unitarias deben ser las primeras en realizarse durante la fase de desarrollo y deben ser implementadas por los desarrolladores.

        .p-4.borde-16.fondo-color-sistema-j
          .row.align-items-center
            .col-sm-2
              figure.mb-4.mb-lg-0
                img.mx-auto(src="@/assets/curso/temas/7.svg",style="max-width: 57px;")
            .col-sm-10
              p.mb-0.fw-bold De acuerdo a Mera (2016) también se las conoce como #[em unit testing] son pequeños #[em tests] en los cuales se revisa que el comportamiento de un objeto y su lógica funcione adecuadamente.
      .col-lg-4.order-first.order-lg-last
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/8.png",style="max-width: 388px;")

    p.mb-4 Generalmente, se llevan a cabo durante la fase de desarrollo de las aplicaciones o software. Esta tarea es ejecutada por los programadores, aunque los aseguradores de calidad también pueden participar en su realización. Las razones para desarrollar este tipo de pruebas incluyen:


    


      
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
