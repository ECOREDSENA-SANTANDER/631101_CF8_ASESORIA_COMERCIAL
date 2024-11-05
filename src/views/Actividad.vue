<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
export default {
  name: 'ActividadDidactica',
  data: () => ({
    cuestionario: {
      tema: 'La postventa',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> Identificar la apropiación de los contenidos en la temática sobre la postventa.',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es el elemento clave en el ciclo dinámico de ventas que permite que una venta realizada hoy se repita mañana?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'El producto', esCorrecta: false },
            { id: 'b', texto: 'El precio', esCorrecta: false },
            { id: 'c', texto: 'El cliente', esCorrecta: true },
            { id: 'd', texto: 'La competencia', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Quién debe considerar las etapas de atención al cliente y servicio postventa para asegurar una relación continua con el cliente en las MiPymes?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'El proveedor', esCorrecta: false },
            { id: 'b', texto: 'El cliente', esCorrecta: false },
            { id: 'c', texto: 'El vendedor', esCorrecta: true },
            { id: 'd', texto: 'El gerente', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Qué proceso requiere decidir qué hacer, cómo hacerlo y con qué hacerlo para asegurar la satisfacción y fidelización del cliente?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Ventas iniciales', esCorrecta: false },
            { id: 'b', texto: 'Postventa', esCorrecta: true },
            { id: 'c', texto: 'Marketing', esCorrecta: false },
            { id: 'd', texto: 'Producción', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué está cubriendo un cliente cuando compra un producto o servicio?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Un deseo', esCorrecta: false },
            { id: 'b', texto: 'Una necesidad', esCorrecta: true },
            { id: 'c', texto: 'Una moda', esCorrecta: false },
            { id: 'd', texto: 'Un capricho', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Qué es más probable que ocurra cuando un cliente queda altamente satisfecho con su experiencia de compra?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Reclamo', esCorrecta: false },
            { id: 'b', texto: 'Devolución', esCorrecta: false },
            { id: 'c', texto: 'Recompra', esCorrecta: true },
            { id: 'd', texto: 'Queja', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Quiénes suelen establecer servicios de atención al cliente y postventa de forma separada?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Proveedores', esCorrecta: false },
            { id: 'b', texto: 'Clientes', esCorrecta: false },
            { id: 'c', texto: 'MiPymes', esCorrecta: false },
            { id: 'd', texto: 'Organizaciones', esCorrecta: true },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Qué proceso es fundamental para seguir de cerca los indicadores propuestos y tomar acciones adecuadas para implementar mejoras?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Evaluación', esCorrecta: false },
            { id: 'b', texto: 'Planificación', esCorrecta: true },
            { id: 'c', texto: 'Ejecución', esCorrecta: false },
            { id: 'd', texto: 'Control', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Cuál de las siguientes características es fundamental para guiar el desarrollo de un proyecto y determinar su dirección?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Recursos', esCorrecta: false },
            { id: 'b', texto: 'Actividades', esCorrecta: false },
            { id: 'c', texto: 'Objetivo', esCorrecta: true },
            { id: 'd', texto: 'Duración', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué tipo de servicios están relacionados con la motivación del cliente, como felicitaciones en su cumpleaños o llamadas para preguntar sobre la satisfacción de su compra?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Técnicos', esCorrecta: false },
            { id: 'b', texto: 'Psicológicos', esCorrecta: true },
            { id: 'c', texto: 'Operativos', esCorrecta: false },
            { id: 'd', texto: 'Administrativos', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Qué tipo de servicios se refieren a acciones como ofrecer descuentos especiales, tarjetas de puntos y llamadas de invitación a promociones y concursos?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Operativos', esCorrecta: false },
            { id: 'b', texto: 'Promocionales', esCorrecta: true },
            { id: 'c', texto: 'Informativos', esCorrecta: false },
            { id: 'd', texto: 'Relacionales', esCorrecta: false },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado:
        '¡Excelente!  Felicitaciones, has superado la actividad, continúe así de bien con sus habilidades técnicas para la postventa.',
      mensaje_final_reprobado:
        'Lo siento, no es correcto, pero no se desanime, continúe su proceso de formación repasando los conceptos del componente formativo e inténtelo de nuevo.',
    },
  }),
}
</script>
