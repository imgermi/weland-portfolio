<template>
  <main class="nosotros">
    <section class="hero">
      <div class="container">
        <h1 class="hero__title">Somos Weland</h1>
        <h2 class="hero__sub">Somos personas enamoradas de <br/> la tecnología y de los desafíos digitales. Como <br/> sabemos que hoy en día la atención es <br/> corta, te contamos las 7 cosas que<br/> tenés que saber de nosotros:</h2>
      </div>
    </section>
    <section class="nosotros__checklist">
      <div class="container">
        <ul>
          <li>En cada proyecto, te sumás a Weland por un tiempo. No se trata de decir “Te pago por el sitio, hacelo y listo” sino que nos involucramos al 100% en tu modelo de negocio, cualquiera sea el servicio que estés buscando.</li>
          <li>Si no sabemos lo que pasa por tu cabeza, no podemos ayudarte. No nos sirve el famoso: “Quiero aparecer primero en Google porque me dijeron que tengo que estar”. Vamos a contestar: “Quizás sea cierto, pero probablemente tu negocio tenga otro rumbo que no conocés todavía”.</li>
          <li>Quizás se haya cruzado por tu cabeza que tu proyecto siga el trío “rápido, bueno y barato”. Con nosotros no funciona así, las buenas decisiones llevan tiempo.</li>
          <li>La fórmula del éxito no la patentamos nosotros, preferimos dedicar el tiempo y esfuerzo necesario al proyecto y que eso te dé un resultado real. No vamos a garantizarte el éxito: hacemos, medimos, aprendemos e iteramos.</li>
          <li>No estamos casados con ninguna filosofía ni proceso de trabajo, cada proyecto es un mundo aparte, el tuyo incluido.</li>
          <li>Buscamos ser un medio para; no queremos ser una solución. La solución la construimos con vos, desde el minuto cero hasta los resultados. Desde el 'lápiz y papel’ hasta la tangible.</li>
          <li>Como verás, un punto fundamental para nosotros es construir relaciones: si todos los puntos anteriores se cumplen, vamos a pasar de ser empresa-cliente, a ser un equipo.</li>
        </ul>
        <p class="quote">Con cada proyecto, soñamos con brindar soluciones que no solo sirvan para cumplir los objetivos de nuestros clientes, sino también para que los usuarios encuentren lo que están buscando y disfruten del proceso que les da esa experiencia.</p>
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