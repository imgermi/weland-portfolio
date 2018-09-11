<template>
  <main class="contacto">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Nos gusta <br/> tu iniciativa.</h1>
        <h2 class="hero__sub">Quizás quieras algunas cosas que no sabés <br/> nombrar, pero nosotros si sabemos como se <br/> llaman. Envianos tu consulta, y a la <br/> brevedad, te contactamos.</h2>
      </div>
    </section>
    <section class="contacto__form">
      <div class="container">
        <form action="">
          <input type="text" placeholder="Nombre">
          <input type="email" placeholder="Email">
          <input type="tel" placeholder="Tel">
          <input type="text" placeholder="Entre">
          <input type="text" placeholder="Y">
          <textarea name="" id="" cols="30" rows="10" placeholder="Contanos sobre el proyecto"></textarea>
          <button type="submit" class="btn__underlined">Enviar</button>
        </form>
      </div>
    </section>
    <section class="trabajos__listado">
      <div class="container">
        <h4 class="section__title">Algunas de las cosas <br> que hicimos</h4>
        <div class="trabajos-container">
          <nuxt-link to="" class="trabajos__listado--trabajo">
            <img src="~/assets/images/case-studies/vitroblock/vitroblock-mockup.jpg" alt="">
            <h3>Vitroblock</h3>
            <span>Consultoría Google Ads</span>
          </nuxt-link>
          <nuxt-link to="" class="trabajos__listado--trabajo">
            <img src="~/assets/images/case-studies/vendexa/vendexa-interiores-mockup.jpg" alt="">
            <h3>Vendexa Interiores</h3>
            <span>Tienda Online</span>
          </nuxt-link>                    
        </div>
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