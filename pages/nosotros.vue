<template>
  <main class="nosotros">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Somos Weland</h1>
        <h2 class="hero__sub">Somos personas enamoradas de <br/> la tecnología y de los desafíos digitales. Como <br/> sabemos que hoy en día la atención es <br/> corta, te contamos las 7 cosas que<br/> tenés que saber de nosotros:</h2>
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