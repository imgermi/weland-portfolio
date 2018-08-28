<template>
  <main class="home">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Marcas. Productos. <br/> Estrategias. Resultados.</h1>
        <h2 class="hero__sub">Somos una agencia digital <br/> enfocada en resolver problemas a <br/> través de diseño y marketing.</h2>
      </div>
    </section>
    <section class="featured">
      <div class="container">
        <article class="featured__img"></article>
        <article class="featured__text">
          <span class="section__pretitle">Proyecto destacado</span>
          <h3 class="section__title">Fucer App</h3>
          <ul class="services__list">
            <li>Estrategia de producto</li>
            <li>UX</li>
            <li>Desarrollo</li>
            <li>Lanzamiento</li>
          </ul>
          <a href="" class="btn">Ver más</a>
        </article>
      </div>
    </section>
    <section class="services">
      <div class="container">
        <article>
          <span class="section__pretitle">Nuestros servicios</span>
          <h3 class="section__title">Lo que hacemos</h3>
        </article> 
        <article>
          <p>Trabajamos junto a startups y empresas construyendo estrategias enfocadas en las necesidades de su audiencia para ayudar a escalar su presencia online.</p>
          <a href="" class="btn">Ver más</a>
        </article>
      </div>
    </section>
    <section class="blog">
      <div class="container">
        <article>
          <span class="section__pretitle">Nuestro proceso</span>
          <h3 class="section__title">Ideas. Data. Más data.</h3>
          <p>Tratamos de documentar todo nuestro proceso de trabajo: desde el análisis, el trato con el cliente, los mates con o sin azúcar y cómo nos llevamos con cada desafío.</p>
        </article> 
        <article>
          <a href="">
            <p>Titulo artículo</p>
            <a href="">> Ver más</a>
          </a>
          <a href="">
            <p>Titulo artículo</p>
            <a href="">> Ver más</a>
          </a>
          <a href="">
            <p>Titulo artículo</p>
            <a href="">> Ver más</a>
          </a>                    
        </article>
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