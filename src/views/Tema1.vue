<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Postventa

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-md-10.col-lg-4
        img(src='@/assets/curso/temas/tema1/img1.png', alt='')(data-aos="fade-right")
      .col-sm-12.col-md-12.col-lg-8
        p La postventa, según Sale Forje (2018), es “la parte de la atención al cliente que reúne todas las estrategias pensadas para mejorar la experiencia después de la compra y mantener una relación duradera con los clientes, siempre correspondiendo a sus expectativas y necesidades”.
        p El servicio postventa para Pérez (2013) es “el conjunto de mecanismos y tareas que emplea la organización para, una vez efectuada la venta, lograr la satisfacción total del cliente con el objetivo de que se repita la compra, recomiende la marca o el producto, entre otras” (p. 184).
        .row.bgmoradoclaro(data-aos="fade-left")
          p.p-5 Es recomendable que el vendedor le de claridad al cliente, sobre todo cuando se hacen ventas por transacciones, “todos los detalles sobre el servicio, los pagos, transportes y organización” (Artal, 2010, p. 326).

    p.mt-5.mb-5.text-center Como actividades de postventa o seguimiento a la venta, Artal (2010) señala:
    .row.justify-content-center.mb-5
      .col-sm-12.col-md-12.col-lg-5(data-aos="fade-right")
        ol.lista-ol--cuadro.lista-ol--separador.fa-ol
          li
            .lista-ol--cuadro__vineta
              span 1
            span.mb-0 La atención en los cobros.
          li
            .lista-ol--cuadro__vineta
              span 2
            span.mb-0 La gestión de impagados.
          li
            .lista-ol--cuadro__vineta
              span 3
            span.mb-0 El cumplimiento correcto de la entrega de pedidos.
          li
      .col-sm-12.col-md-12.col-lg-5(data-aos="fade-left")
        ol.lista-ol--cuadro.lista-ol--separador.fa-ol
          li
            .lista-ol--cuadro__vineta
              span 1
            span.mb-0 La solución de las quejas. 
          li
            .lista-ol--cuadro__vineta
              span 2
            span.mb-0 Las reclamaciones.
          li
            .lista-ol--cuadro__vineta
              span 3
            span.mb-0 Los servicios de reparación y mantenimiento (p. 327).
          li

    p.mt-5.mb-5.text-center Según Pérez (2013), las ventajas e inconvenientes del servicio postventa son las siguientes:   

    .row.justify-content-center.align-items-center.mb-2
      .col-12.col-md-12.col-lg-10

        .titulo-sexto.color-secundario.mb-4
          h5 Tabla 1. 
          | Ventajas e inconvenientes del servicio postventa en la empresa

        .tabla-a.color-primario(data-aos="zoom-in")
          table
            caption Nota. Adaptado de Pérez (2013).
            thead
              tr
                th.bgazulclaro Ventajas
                th.bgazulclaro Inconvenientes
            tbody
              tr
                td.bggristabla Produce una mayor satisfacción del cliente.
                td.bggristabla Implica ciertos gastos.
              tr
                td Mejora la imagen de la empresa y del producto.
                td Necesita de control.
              tr
                td.bggristabla Mejora el conocimiento directo del mercado.
                td.bggristabla Produce un posible aumento del número de reclamaciones.
              tr
                td Implica la posible fidelización del cliente.
                td Supone mayores exigencias de servicio y calidad.
              tr
                td.bggristabla Supone un probable incremento de las ventas.
                td.bggristabla Provoca mayores necesidades de personal.

    separador
    #t_1_1.titulo-segundo.mb-4
      h2 1.1 Etapas de la postventa
    p La venta debe considerarse un ciclo dinámico con el cliente, de modo que la venta realizada hoy debe repetirse mañana y así sucesivamente. En los productos de consumo masivo, esto es fundamental con los mismos productos. Sin embargo, en productos y servicios que no son de compra habitual, se pueden ofrecer productos y servicios complementarios. Por ejemplo, a una persona que compra un vehículo familiar se le pueden vender repuestos, garantías de mantenimiento, reparaciones, entre otros.
    p Para lograr que el cliente regrese se debe montar un programa de fidelización que según Escamilla (2020) “consiste en desarrollar una relación positiva entre los consumidores y la empresa, para que regresen a comprar tus productos o servicios”. La postventa debe seguir unas etapas y acciones que lleve al cliente a regresar al negocio, esto es:


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
