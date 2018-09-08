<template>
  <main class="servicios">
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