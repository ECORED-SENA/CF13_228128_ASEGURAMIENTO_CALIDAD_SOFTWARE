<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.mb-4.align-items-center
      .col-lg-5(data-aos="fade-right")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/38.png",style="max-width: 505px;")
      .col-lg-7(data-aos="fade-left")

        .fondo-color-sistema-k.p-4.borde-12
          p.mb-4 En este componente formativo, denominado "Aplicación de pruebas de #[em software]", se estudiarán los diferentes elementos necesarios para la realización de pruebas. Por lo tanto, se abordarán las siguientes áreas de aprendizaje: tipos de pruebas funcionales y no funcionales, pruebas ágiles (#[em Agile Testing]) y la elaboración de informes de resultados.
          p.mb-0 Es importante resaltar que, en el desarrollo de aplicaciones web, uno de los principales desafíos es asegurar que la calidad del producto sea óptima y libre de errores. En este contexto, las pruebas de #[em software] constituyen un componente fundamental del proceso de aseguramiento de la calidad y la adopción de buenas prácticas.

    .fondo-color-secundario.p-3.borde-15.text-white(data-aos="fade-down")
      .row.align-items-center
        .col-lg-9
          p.mb-4 Las pruebas de #[em software] engloban el conjunto de actividades realizadas para identificar posibles fallos de funcionamiento, configuración o usabilidad en programas o aplicaciones, mediante la evaluación de su comportamiento. La complejidad e interoperabilidad de los sistemas informáticos, programas y aplicaciones han aumentado significativamente, lo que a su vez ha incrementado las posibilidades de defectos.
          p.mb-0 Para aplicar pruebas de #[em software] eficazmente, se deben estudiar los diferentes elementos que las componen. Así, se profundizará en los tipos de pruebas funcionales y no funcionales, las pruebas ágiles y la elaboración de informes de resultados. Cabe destacar que, en el contexto del desarrollo de aplicaciones web, verificar la óptima calidad del producto sin errores es esencial, haciendo que las pruebas de #[em software] sean un pilar fundamental en el proceso de desarrollo.
        .col-lg-3.order-first.order-lg-last
          figure.mb-4.mb-lg-0
            img.mx-auto(src="@/assets/curso/temas/1.png",style="max-width: 400px;")
    
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
