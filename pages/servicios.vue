<template>
  <main class="servicios">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">¿Qué podríamos <br/> hacer juntos?</h1>
        <h2 class="hero__sub">Creamos marcas, construimos <br/> productos, y también hacemos <br/> cosas de marketing.</h2>
      </div>
    </section>
    <Contacto/>
  </main>
</template>

<script>
  import Contacto from '~/components/Contacto.vue'

  export default {
    components: {
      Contacto
    }
  }
</script>