<template>
  <main class="trabajos">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Brief. Objetivos. <br/> Procesos. Resultados.</h1>
        <h2 class="hero__sub">Lo que pasa después de <br/> 2435,66 mails, varias reuniones <br/> y mucho feedback.</h2>
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