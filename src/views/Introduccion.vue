<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .contenedor-total.d-block.d-lg-none
      figure
        img.mx-auto(src='@/assets/curso/images/tema1/intro_movil.png' alt='Imagen ambiental' style='')
      .contenedor-text.mg-top
        .row.justify-content-center
          .col-auto.px-4.py-2.p-md-4
            p.mb-0 Le damos la bienvenida al componente formativo <b>“Generalidades de computación en la nube”</b>. Para comenzar el recorrido por el mismo, visite el recurso didáctico que se muestra a continuación:
  

    .contenedor-total.d-none.d-lg-block
      figure
        img.mx-auto(src='@/assets/curso/images/tema1/intro.png' alt='Imagen ambiental' style='')
      .contenedor-text
        .row.justify-content-center.p-4
          .col-auto
            p.aling-12.mb-3 Le damos la bienvenida al componente formativo <b>“Generalidades de la computación en la nube”</b>. Para comenzar el recorrido por el mismo, visite el recurso didáctico que se muestra a continuación:
  
    
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/56s842xCrCo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    figcaption Video. Generalidades de la computación en la Nube     

      
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
