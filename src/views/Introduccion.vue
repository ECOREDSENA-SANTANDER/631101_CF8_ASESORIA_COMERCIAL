<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p.mb-4 En este componente, exploraremos la importancia de mantener una relación sólida con nuestros clientes después de la compra, así como las estrategias efectivas para garantizar su satisfacción y lealtad. Aprenderemos cómo un servicio postventa excepcional no solo resuelve problemas, sino que también crea oportunidades para el crecimiento y la fidelización. ¡Comencemos a descubrir cómo podemos convertir cada interacción en una oportunidad para fortalecer nuestra marca!

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-md-12.col-lg-10
        figure
          .video
            iframe(iframe width="560" height="315" src="https://www.youtube.com/embed/c2PD39QIU2Y?si=PIp8MwKUugquQSLB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)
          figcaption Video: La posventa.

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
