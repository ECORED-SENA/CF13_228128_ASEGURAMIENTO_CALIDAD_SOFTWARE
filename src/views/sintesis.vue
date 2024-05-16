<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 A continuación, se muestra un mapa conceptual con los elementos más importantes desarrollados en este componente.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="La síntesis presenta las pruebas de software que aseguran la calidad ISO/IEC evaluando aspectos funcionales y no funcionales, incluyendo pruebas unitarias, de integración y de rendimiento. Estas pruebas permiten verificar el comportamiento individual de los módulos, la interacción entre componentes y la eficiencia bajo condiciones de trabajo específicas. Su implementación es clave para identificar errores, optimizar recursos y garantizar la confiabilidad y el rendimiento esperado del producto final.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
