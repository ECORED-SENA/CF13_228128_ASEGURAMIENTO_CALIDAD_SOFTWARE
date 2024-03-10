<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Elaboración del plan de mejora
    
    .row.align-items-center.mb-4
      .col-lg-5(data-aos="fade-right")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/107.png",style="max-width: 505px;")
      .col-lg-7(data-aos="fade-left")
        .fondo-color-sistema-k.p-4.borde-12
          p.mb-0 Cuando una organización alcanza el éxito, suele deberse a su capacidad para integrar la mejora continua en cada uno de sus procesos y actividades diarias. La mejora se logra cuando la organización toma en cuenta tanto sus fortalezas como sus debilidades. Sin embargo, identificar la situación actual de la organización a través de un diagnóstico es también crucial. Una vez realizado el diagnóstico, se puede establecer la estrategia a seguir para que los destinatarios de los servicios perciban de manera significativa la mejora implementada.
    .cont-titulo-decorativo.p-2.mt-5.mb-4(data-aos="fade-left")
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Identificar el área de mejora
    
    p.mb-4(data-aos="fade-right") Una vez elaborado el diagnóstico, se conocen las principales fortalezas y debilidades. Por lo tanto, es importante identificar las áreas de mejora apoyándose en las fortalezas para lograr superar las debilidades, siendo esta una opción de cambio óptima. A continuación, se muestra una tabla como una opción para identificar el área de mejora de acuerdo con las fortalezas y debilidades.

    .titulo-sexto.color-acento-contenido(data-aos="fade")
      p.mb-0 #[b Tabla 3.] Ejemplo estructura de tabla de fortalezas, debilidades y área de mejora.
    
    .tabla-a.color-acento-contenido.mb-5.bg-white.mb-5(data-aos="zoom-in-up")
      table
        thead
          tr
            th Fortalezas 
            th Debilidades
            th Áreas de mejora
        tbody
          tr
            td #[b 1.]
            td #[b 1.]
            td #[b 1.]
          tr
            td #[b 2.]
            td #[b 2.]
            td #[b 2.]
          tr
            td #[b 3.]
            td #[b 3.]
            td #[b 3.]

    p.mb-4(data-aos="fade") Resolver problemas y mejorar un área específica comienza por identificar las causas que los originaron. Por lo tanto, existen varias herramientas metodológicas diseñadas para esta finalidad. A continuación, se mencionan algunas de ellas:

    .slyder-a-personalizado-1.px-3.pb-3.pt-5.mb-5(data-aos="flip-up")
      .slyder-a-personalizado-1__fondo
        figure.fig-flotante(style="left: 0;top: -140px;max-width:118px;")
          img(src="@/assets/curso/temas/55.svg",style="max-width:118px;")
        figure.fig-flotante(style="z-index: 1;right: 10px;top: 10px;max-width:88px;")
          img(src="@/assets/curso/temas/56.svg",style="max-width:87px;")
        figure.fig-flotante(style="right: -70px;top: -115px;max-width:173px;")
          img(src="@/assets/curso/temas/57.svg",style="max-width:173px;")
        figure.fig-flotante(style="left: 35%;bottom: -160px;max-width:227px;")
          img(src="@/assets/curso/temas/58.svg",style="max-width:227px;")

      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center
          .col-lg-5
            .pt-lg-5
              h4.titulo-item-slyder Diagrama de espina de pescado comentado
          .col-lg-5.order-first.order-lg-last
            figure.mb-4.mb-lg-0
              img.mx-auto(src="@/assets/curso/temas/108.png",style="max-width: 505px;",alt="El diagrama de espina de pescado comentado detalla causas de un problema no especificado, agrupadas en seis principales. A la izquierda, las causas son la falta de consideración de colegas, mala supervisión con moral baja y falta de formación que conduce a falta de conocimientos. A la derecha, se mencionan la falta de acceso a información, malas condiciones de trabajo con alta rotación de personal y recursos humanos inadecuados para la elaboración de memorias.")
        .row.justify-content-center.align-items-center
          .col-lg-5
            .pt-lg-5
              h4.titulo-item-slyder El diagrama de espina (causa-efecto)
          .col-lg-5.order-first.order-lg-last
            figure.mb-4.mb-lg-0
              img.mx-auto(src="@/assets/curso/temas/109.png",style="max-width: 505px;",alt="El diagrama de espina mostrado es una herramienta de análisis causa-efecto que estructura jerárquicamente las causas principales y sus causas secundarias, todas vinculadas a un efecto central, para desglosar y entender las razones detrás de un problema específico.")
        .row.justify-content-center.align-items-center
          .col-lg-5
            .pt-lg-5
              h4.titulo-item-slyder Diagrama de pareto
          .col-lg-5.order-first.order-lg-last
            figure.mb-4.mb-lg-0
              img.mx-auto(src="@/assets/curso/temas/110.png",style="max-width: 505px;",alt="El diagrama de Pareto exhibe la distribución y el impacto relativo de distintos tipos de incidencias. Se cuantifican las incidencias por categoría y se muestra el porcentaje acumulado de su impacto para priorizar problemas en base a su frecuencia y significancia.")
        .row.justify-content-center.align-items-center
          .col-lg-5
            .pt-lg-5
              h4.titulo-item-slyder Tormenta de ideas
          .col-lg-5.order-first.order-lg-last
            figure.mb-4.mb-lg-0
              img.mx-auto(src="@/assets/curso/temas/111.png",style="max-width: 505px;",alt="Tormenta de ideas es una traducción correcta del término inglés \"brainstorming\". Se utiliza para referirse a una técnica de grupo para generar ideas creativas y soluciones a problemas, donde se fomenta la participación de todos los miembros y se valora la cantidad sobre la calidad de las ideas, con el objetivo de explorar el mayor número de opciones posibles.")

    p.mb-4(data-aos="fade") El uso de estas herramientas contribuye a un análisis más profundo del problema y se convierten en directrices clave al momento de establecer acciones de mejora.

    h4.mb-4 Formular el objetivo

    .row.align-items-center.mb-5(data-aos="fade-left")
      .col-lg-5
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/112.png",style="max-width: 505px;")
      .col-lg-7
        .fondo-color-sistema-k.borde-12.p-4
          p.mb-0 Una vez conocidas e identificadas las causas del problema y las áreas de mejora, se pueden establecer los objetivos y determinar el tiempo para lograrlos. Al momento de escribir los objetivos, estos deben ser:

          ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
            li
              i.fas.fa-cube(style="color: #273A89;")
              span Precisos o concretos.
            li
              i.fas.fa-cube(style="color: #273A89;")
              span Expresar de forma indiscutible el resultado que se quiere alcanzar.
            li
              i.fas.fa-cube(style="color: #273A89;")
              span Su redacción debe ser clara.
            li
              i.fas.fa-cube(style="color: #273A89;")
              span Deben ser alcanzables, comprensibles y flexibles, es decir que se puedan cumplir, interpretar y en algún caso extremo modificar.

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 2.1  Seleccionar las acciones de mejora

    .row.align-items-center.mb-4
      .col-lg-7(data-aos="fade-right")
        p.mb-4 En este punto, es necesario seleccionar las opciones de mejora para dar prioridad a las más adecuadas. Para ello, se pueden emplear técnicas como la del grupo nominal y la tormenta de ideas, entre otras. Estas técnicas permiten establecer acciones de mejora que se convierten en soluciones para las debilidades identificadas. Esto significa que, para alcanzar los objetivos establecidos, se debe contar con una lista de las principales actuaciones.

        .fondo-color-sistema-k.p-4.borde-13
          p.mb-0 A continuación, se presenta una tabla utilizada para seleccionar las acciones de mejora. Para ello, es imprescindible haber identificado previamente el problema, la causa y su objetivo.

      .col-lg-5(data-aos="fade-left")
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/113.png",style="max-width: 505px;")

    .titulo-sexto.color-acento-contenido(data-aos="zoom-in-up")
      p.mb-0 #[b Tabla 4.] Ejemplo estructura de tabla sobre acciones de mejora.
    
    .fondo-gradiente-9.posicion-1
      .fondo-gradiente-contenido
        .tabla-a.color-acento-contenido.mb-5.bg-white.mb-5(data-aos="flip-up")
          table
            thead
              tr
                th.text-start ÁREA DE MEJORA N.º 1: 
                th 
            tbody
              tr
                td #[b Descripción del problema]
                td
              tr
                td #[b Causas que provocan el problema]
                td
              tr
                td #[b Objetivo a conseguir]
                td
              tr
                td #[b Acciones de mejora]
                td
              tr
                td #[b Beneficios esperados]
                td

        Separador

        #t_2_2.titulo-segundo.color-acento-contenido
          h2 2.2 Realizar una planeación

        p.mb-4(data-aos="fade") El listado de las principales actuaciones se genera sin tener en cuenta un orden de prioridad especifico. No obstante, ciertas restricciones inherentes a las acciones pueden limitar su inicio, o incluso llevar a la posible eliminación o aplazamiento del plan de mejora. Por lo tanto, es crucial conocer las restricciones que limitan su viabilidad. Determinar un orden óptimo no se basa únicamente en identificar las acciones relacionadas con los factores de mayor urgencia; otros criterios también se consideran al tomar esta decisión. A continuación, se describen algunos de estos criterios:

        Separador 

        #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade")
          h2 2.3 Seguimiento del plan de mejora

        .row.mb-4
          .col-lg-8(data-aos="fade-right")
            p.mb-4 En este momento, se procede a elaborar un cronograma para la implantación y seguimiento de las acciones de mejora. Dicho cronograma organizará de manera ordenada las prioridades junto con los plazos establecidos para su desarrollo.
            p.mb-0 Una vez seleccionadas las acciones por orden de prioridad, se construye el plan de mejoras. Este incluirá los elementos necesarios para realizar un seguimiento detallado del plan, garantizando así su eficiencia y eficacia. Todo ello teniendo en cuenta la tabla presentada en la siguiente tabla:
          .col-lg-4(data-aos="fade-left")
            figure.mb-4.mb-lg-0
              img.mx-auto(src="@/assets/curso/temas/114.png",style="max-width: 400px;")
        
        .titulo-sexto.color-acento-contenido(data-aos="fade")
          p.mb-0 #[b Tabla 5.] Estructura plan de mejora.

        
        .tabla-a.color-acento-contenido.bg-white
          table
            thead
              tr
                th Acciones de mejora
                th Tareas
                th Responsable de tarea
                th Tiempos (inicio-final)
                th Recursos necesarios
                th Financiación
                th Indicador seguimiento
                th Responsable seguimiento
            tbody
              tr
                td
                td
                td
                td
                td
                td
                td
                td
              tr
                td
                td
                td
                td
                td
                td
                td
                td
    
      

    

</template>

<script>
export default {
  name: 'Tema2',
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
