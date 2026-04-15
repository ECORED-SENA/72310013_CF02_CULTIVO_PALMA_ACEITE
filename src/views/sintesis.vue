<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .row.mb-5
      .col-12.ps-3(style="border-left: 10px solid #39A900;") 
        h3.mb-1 Cultivo de palma de aceite
        p.mb-0 
          | Síntesis:           
          | Cultivo de palma de aceite: mantenimiento del cultivo y cosecha del fruto.
    p.mt-5 A continuación, se presenta una síntesis de la temática estudiada en el componente formativo:
    .row.justify-content-center
      .col-lg-10.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="El esquema conceptual presenta el manejo integral del cultivo de palma de aceite, relacionando mantenimiento, cosecha y planificación productiva. Integra prácticas agronómicas, control sanitario, nutrición, agua, poda, madurez del racimo, pronósticos y transporte para optimizar productividad y calidad del aceite.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
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
