<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .row.align-items-center.fondo-sintesis.p-3.mb-5
      .col-lg-12.mb-4.mb-lg-0.mb-5 
        .row.justify-content-evenly
          .col-lg-6(data-aos="fade-right")
            p.mb-4 La computación en la nube permite que los consumidores y las empresas gestionen archivos y utilicen aplicaciones sin necesidad de instalarlas, lo cual puede hacerse en cualquier computadora con acceso a internet.
            .cajon.color-custom.p-3.mb-md-0.mb-4
              p.mb-0 Además, es útil como modelo de negocio, puesto que el <i>software</i> reduce los costos mediante servidores centralizados en internet, en lugar de servidores locales, al eliminar gastos de mantenimiento, licencias y <i>hardware</i> necesario para mantener los servidores, permite que las empresas puedan ejecutar aplicaciones fluida y eficientemente.
          .col-lg-5(data-aos="fade-left") 
            img(src='@/assets/curso/images/tema3/img_1.png', alt='')  

    .row.align-items-start.bg-tema-sintesis.mb-5.mb-md-0
      .col-lg-12.px-lg-2.px-4.py-4.pb-md-5(data-aos="fade-right")
        .row.align-items-center.justify-content-evenly
          .col-lg-4.col-md-4-col-10.mb-md-0.mb-4.mb-lg-0(data-aos="fade-right")
            img(src='@/assets/curso/images/tema3/img_2.svg' alt='Imagen decorativa')
          .col-lg-7.col-md-7.text-white.esquina.p-3(data-aos="fade-left")
            p La computación en la nube hace que sea posible que los usuarios accedan a aplicaciones en servidores centralizados que se basan en la infraestructura de la nube, pudiendo así las aplicaciones funcionar en la nube y facilitando su implementación sin costo alguno, manteniendo varias capas de <i>hardware</i> y <i>software</i>. El siguiente mapa ofrece una vista rápida #[br] de los contenidos de este componente formativo:

      
    p.my-3 El siguiente mapa ofrece una vista rápida de los contenidos de este componente formativo:

    .row.justify-content-center
      .col-lg-12.mb-4(data-aos="fade")
        img(src="@/assets/curso/images/tema3/img_3.svg" alt="")


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
