<template>
  <main class="home">
    <div class="wave top-wave">
      <svg width="684" height="403" viewBox="0 0 684 403" fill="none" xmlns="http://www.w3.org/2000/svg">
        <mask id="mask0" mask-type="alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="684" height="404">
        <rect y="0.000366211" width="684" height="403" fill="#C4C4C4"/>
        </mask>
        <g mask="url(#mask0)">
        <path opacity="0.8" d="M681.364 -314.811C461.253 -394.635 348.441 -496.651 319.548 -537.681L-7.25193 -7.14096C46.8831 49.4381 198.401 175.296 371.392 226.095C544.383 276.894 679.072 392.386 724.793 443.782L1051.59 -86.758C1019.9 -129.516 901.475 -234.987 681.364 -314.811Z" fill="#BE0042" fill-opacity="0.06"/>
        <path d="M648.324 -288.214C449.222 -360.419 347.178 -452.698 321.043 -489.811L25.4359 -9.91089C74.4038 41.2677 211.459 155.112 367.939 201.063C524.418 247.013 646.251 351.481 687.608 397.972L983.215 -81.9286C954.544 -120.605 847.425 -216.009 648.324 -288.214Z" fill="#BE0042" fill-opacity="0.06"/>
        </g>
      </svg>
    </div>
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Marcas. Productos. <br/> Estrategias. Resultados.</h1>
        <h2 class="hero__sub">Somos una agencia digital <br/> enfocada en resolver problemas a <br/> través de diseño y marketing.</h2>
      </div>
    </section>
    <section class="featured">
      <div class="container">
        <article class="featured__img">
          <img src="~/assets/images/case-studies/fucer/mockup.jpg" alt="">
        </article>
        <article class="featured__text">
          <span class="section__pretitle">Proyecto destacado</span>
          <h3 class="section__title">Fucer App</h3>
          <ul class="services__list">
            <li>Estrategia de producto</li>
            <li>UX</li>
            <li>Desarrollo</li>
            <li>Lanzamiento</li>
          </ul>
          <!-- <a href="" class="btn">Ver más</a> -->
          <nuxt-link to="/trabajos/fucer-app" class="btn__underlined">Ver más</nuxt-link>
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
          <nuxt-link to="/servicios" class="btn__underlined">Ver más</nuxt-link>
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
          <a href="" class="blog__link">
            <span class="blog__link--date">10/7/2018</span>
            <p class="blog__link--title">Agencia vs Cliente: ¿Quien tiene la <br> última palabra?</p>
            <small class="blog__link--arrow">></small>
          </a>
          <a href="" class="blog__link">
            <span class="blog__link--date">10/7/2018</span>
            <p class="blog__link--title">Aprender haciendo: desarrollando habilidades cuando la situación lo demanda</p>
            <small class="blog__link--arrow">></small>
          </a>
          <a href="" class="blog__link">
            <span class="blog__link--date">10/7/2018</span>
            <p class="blog__link--title">¿Desde que momento somos Consultores en Marketing Digital?</p>
            <small class="blog__link--arrow">></small>
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