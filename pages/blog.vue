<template>
  <main class="blog">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Nos gusta <br/> hacer catarsis.</h1>
        <h2 class="hero__sub">Entre mate y mate, somos personas <br/> reflexivas. Las agencias también pueden tener <br/> sentimientos, y volcamos los nuestros en <br/> papel y palabras sabias. Mentira, <br/> escribimos informalidades en Medium.</h2>
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