<template>
  <main class="contacto">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Nos gusta <br/> tu iniciativa.</h1>
        <h2 class="hero__sub">Quizás quieras algunas cosas que no sabés <br/> nombrar, pero nosotros si sabemos como se <br/> llaman. Envianos tu consulta, y a la <br/> brevedad, te contactamos.</h2>
      </div>
    </section>
    <Blog/>
  </main>
</template>

<script>
  import Blog from '~/components/Blog.vue'

  export default {
    components: {
      Blog
    }
  }
</script>