<template>
  <main class="blog">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Nos gusta <br/> hacer catarsis.</h1>
        <h2 class="hero__sub">Entre mate y mate, somos personas <br/> reflexivas. Las agencias también pueden tener <br/> sentimientos, y volcamos los nuestros en <br/> papel y palabras sabias. Mentira, <br/> escribimos informalidades en Medium.</h2>
      </div>
    </section>
    <section class="blog__listado">
      <div class="container">
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