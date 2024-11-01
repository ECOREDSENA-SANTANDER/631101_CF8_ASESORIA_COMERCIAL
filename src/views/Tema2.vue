<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Herramientas Postventa

    p.mb-4 Para que la estructura del servicio postventa funcione de manera eficaz, Pérez (2013) propone que la empresa cuente con las siguientes herramientas para poder implantar una acción de postventa:

    .row.justify-content-center.align-items-center
      .col-sm-12.col-md-12.col-lg-12
        TabsA.color-acento-botones
          .tarjeta.color-secundario--borde.p-4(titulo="Base de datos de los clientes")
            .row.align-items-center.justify-content-center
              .col-auto
                img(src='@/assets/curso/temas/tema2/tab1-1.png', alt='')
              .col-8
                p Tener listado de los clientes con su información básica, especialmente el teléfono para realizar Telemarketing, y de esta manera comunicarse con los clientes vía telefónica. 
          .tarjeta.color-secundario--borde.p-4(titulo="Correspondencia")
            .row.align-items-center.justify-content-center
              .col-auto
                img(src='@/assets/curso/temas/tema2/tab1-2.png', alt='')
              .col-8
                p Puede utilizar cualquier medio, el usado comúnmente es el correo electrónico, donde pueda comunicar como van las incidencias u otros envíos como catálogos, revistas, u otras invitaciones. 
          .tarjeta.color-secundario--borde.p-4(titulo="Página web y correo electrónico")
            .row.align-items-center.justify-content-center
              .col-auto
                img(src='@/assets/curso/temas/tema2/tab1-3.png', alt='')
              .col-8
                p Contar con una pagina web es hasta hoy el mejor modo más económico y rápido para comunicarse con el cliente.  
          .tarjeta.color-secundario--borde.p-4(titulo="Visita personal")
            .row.align-items-center.justify-content-center
              .col-auto
                img(src='@/assets/curso/temas/tema2/tab1-4.png', alt='')
              .col-8
                p Es el mejor servicio de postventa, pero también el más costoso. 

    separador

    .row.justify-content-center.align-items-center
      .col-sm-12.col-md-12.col-lg-9
        #t_2_1.titulo-segundo.mb-4
          h2 2.1 Importancia del servicio postventa    
        p.mt-5 Cuando un cliente compra un producto o servicio, está cubriendo una necesidad y obtenido una experiencia que de ser altamente satisfecha traería de vuelta a ese cliente en una recompra. Por tanto, tener un servicio postventa le permite a la empresa conocer esas experiencias y adoptar acciones de mejora que mantengan una relación duradera con el cliente y se cuantifique en rentabilidad.
        p.mb-4 Es por eso, que el servicio postventa tiene como propósito fidelizar clientes y que su compra sea más seguida, se debe procurar:
      .col-12.col-md-6.col-lg-3
        img(src='@/assets/curso/temas/tema2/img1.png', alt='')

    .row
      .col-lg-5.col-sm-12.col-md-12
        ol.lista-ol--cuadro.lista-ol--separador.fa-ol
          li
            .lista-ol--cuadro__vineta
              span 1
            span.mb-0 La atención al cliente sea motivo de diferenciación. 
          li
            .lista-ol--cuadro__vineta
              span 2
            span.mb-0 Que los clientes estén satisfechos.
          li
      .col-lg-6.col-sm-12.col-md-12
        ol.lista-ol--cuadro.lista-ol--separador.fa-ol
          li
            .lista-ol--cuadro__vineta
              span 3
            span.mb-0 Que recomienden la empresa.
          li
            .lista-ol--cuadro__vineta
              span 4
            span.mb-0 Identificar reacciones de los clientes con los productos o servicios.
          li

    separador
    #t_2_2.titulo-segundo.mb-4
      h2 2.2 Tipos de servicios postventa

    p.mb-4 Entre los servicios postventa que debe adoptar la empresa, ya sea para productos de larga duración con garantía de fábrica o para compras menos exigentes, Martínez (2021) propone los siguientes tipos de servicios postventa:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.col-12.col-md-12.bgmorado100.borde-redondo-izquierdo.p-0
        .row.justify-content-center.align-items-center.p-5
          .col-6.col-md-6.col-lg-3
            img.mt-4(src='@/assets/curso/temas/tema2/tar1-1.png', alt='')
          .col-sm-12.col-md-12.col-lg-8.bgmoradomedio.mt-5
            h3.mt-2 Los servicios técnicos que se llevan sobre los productos
        .row.justify-content-center.align-items-center
          .col-sm-12.col-md-12.col-lg-9
            p.text-white #[b Instalación:] dependiendo del producto, generalmente se realiza en la vivienda del cliente.
            p.text-white #[b Mantenimiento:] consiste en la revisión y puesta a punto del producto, que incluye limpieza, cambio de piezas y lubricación, de acuerdo con el uso del producto.
            p.mb-5.text-white #[b Reparaciones:] implica la sustitución de piezas defectuosas que impiden el funcionamiento del producto. Si el producto aún está bajo garantía, las reparaciones se realizarán sin costo adicional; sin embargo, si la garantía ha vencido, el cliente deberá cubrir los costos.
      .col-lg-6.col-12.col-md-12.bgmoradomedio.borde-redondo-derecho.p-0
        .row.justify-content-center.align-items-center.p-5
          .col-6.col-md-6.col-lg-3
            img.mt-4(src='@/assets/curso/temas/tema2/tar1-1.png', alt='')
          .col-sm-12.col-md-12.col-lg-8.bgmorado100.mt-5
            h3.mt-2.text-white Los servicios que se prestan a quien adquiere el producto o servicio
        .row.justify-content-center.align-items-center.mb-2.mt-5
          .col-sm-12.col-md-12.col-lg-9.mb-5
            p.mb-5 #[b Adiestramiento para el uso del producto:] orientaciones que ofrece la empresa al cliente para su uso eficaz.
            p.mb-5 #[b Mantenimiento:] Consiste en la revisión y puesta a punto del producto, que incluye limpieza, cambio de piezas y lubricación, de acuerdo con el uso del producto.

    p.mb-4.text-center Los aportes que hace Pérez (2013) sobre los tipos de servicios son los siguientes, como se detalla en la tabla 5:

    p TABLA

    p.mb-4.text-center Luego de realizarse la venta de los productos y servicios, la empresa puede hacer distintas actividades dirigidas según Pérez (2013) a:

    P INFOGRAFIA CON PUNTOS CALIENTES

    separador
    #t_2_3.titulo-segundo.mb-4
      h2 2.3 Fases del servicio postventa

    p.mb-4 En el desarrollo del servicio postventa luego que el cliente ha realizado su compra, la empresa debe incorporar a sus protocolos acciones que dan fortaleza al seguimiento de clientes y este lo agradece. Al respecto Douglas (2020) sostiene aspectos a tener en cuenta.

    figure
      .video
        iframe(iframe width="560" height="315" src="https://www.youtube.com/embed/3Q8v2opknoo?si=Sj-5L7LkKKXzeS5m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen)



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
