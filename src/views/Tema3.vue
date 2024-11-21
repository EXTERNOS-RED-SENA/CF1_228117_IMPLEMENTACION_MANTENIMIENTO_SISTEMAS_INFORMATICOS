<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Herramientas de gestión
    
    p(data-aos="fade-up" data-aos-duration="850") Son aplicaciones y sistemas tecnológicos para organizar, monitorear y optimizar el flujo de trabajo en el soporte técnico y atención al cliente en la reparación de equipos. Estas herramientas mejoran la eficiencia operativa, contribuyen a una experiencia de servicio más transparente y satisfactoria para el cliente. Entre las funcionalidades más útiles se encuentran las siguientes:

</template>

<script>
export default {
  name: 'Tema3',
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
