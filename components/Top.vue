<template>
  <header>
    <div class="container">
      <nuxt-link to="/">
        <svg class="logo" width="150" height="50" viewBox="0 0 150 50" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="150" height="49.0289" fill="black" fill-opacity="0"/>
          <rect width="150" height="49.0289" fill="black" fill-opacity="0"/>
          <rect width="48.7752" height="49.0289" fill="black" fill-opacity="0"/>
          <rect width="43.8344" height="34.6644" fill="black" fill-opacity="0" transform="translate(4.9408)"/>
          <path d="M35.7264 18.6234L40.4139 31.6724C40.0339 31.6724 39.6538 31.6724 39.2737 31.6724C35.8531 31.7991 32.4325 32.1792 30.4055 32.5592L35.7264 18.6234Z" fill="#BE0042"/>
          <path d="M48.6487 1.64696V11.2754L42.3142 26.6048L35.8531 8.4882L29.0118 26.4781L22.424 9.62841H18.3699L27.7449 32.9393C21.5371 34.0795 17.2297 34.4596 17.2297 34.4596C10.0084 35.3464 4.9408 33.066 4.9408 33.066V1.39359C4.9408 1.39359 10.0084 3.54731 17.2297 2.78717C17.2297 2.78717 22.1706 2.28041 28.8851 1.14021C28.8851 1.14021 34.2061 0.12669 39.527 -6.04103e-08C44.5946 -6.04103e-08 48.6487 1.64696 48.6487 1.64696Z" fill="#BE0042"/>
          <path d="M44.0877 32.0525L48.7752 21.0305V33.3194C48.6485 33.3194 46.8748 32.5592 44.0877 32.0525Z" fill="#BE0042"/>
          <path d="M2.15372 -6.04103e-08V43.5812L-1.20821e-07 49.0289V-6.04103e-08H2.15372Z" fill="#BE0042"/>
          <rect width="98.8177" height="26.2247" fill="black" fill-opacity="0" transform="translate(51.1823 8.48819)"/>
          <path d="M63.978 13.4291V10.1352H53.2093L51.1823 14.9494V33.1927H63.978V29.8987H54.7296V22.1707H63.7246V18.8767H54.7296V13.3024H63.978V13.4291Z" fill="#BE0042"/>
          <path d="M72.0858 10.1352V30.0254H78.9271V33.3194H68.6652V10.1352H72.0858Z" fill="#BE0042"/>
          <path d="M97.0438 27.6183H87.162L84.6282 33.1927H80.8275L92.2296 8.6149L103.252 33.1927H99.4509L97.0438 27.6183ZM95.6502 24.3244L92.2296 16.4697L88.6823 24.3244H95.6502Z" fill="#BE0042"/>
          <path d="M106.292 33.3193V8.48819L123.142 26.098V10.1352H126.689V34.7129L109.713 17.1031V33.3193H106.292Z" fill="#BE0042"/>
          <path d="M132.137 33.3194V10.1352H136.951C139.231 10.1352 141.132 10.3885 142.525 10.7686C143.919 11.2754 145.313 12.0355 146.453 13.049C148.86 15.2027 150 18.1166 150 21.6639C150 25.2112 148.733 28.1251 146.326 30.2788C145.059 31.419 143.792 32.1791 142.399 32.5592C141.132 32.9393 139.358 33.1927 136.951 33.1927H132.137V33.3194ZM135.684 30.0254H137.204C138.725 30.0254 140.118 29.8987 141.132 29.5187C142.145 29.1386 143.159 28.6318 143.919 27.8717C145.693 26.3514 146.453 24.1977 146.453 21.7906C146.453 19.2568 145.566 17.2298 143.919 15.5828C142.399 14.1892 140.118 13.4291 137.204 13.4291H135.684V30.0254Z" fill="#BE0042"/>
        </svg>
      </nuxt-link>
      <button :class="'hamburger hamburger--elastic' + (menuActivo ? ' is-active' : '')" type="button" v-on:click="openMenu">
        <span class="hamburger-box">
          <span class="hamburger-inner"></span>
        </span>
      </button>
      <nav :class="(menuActivo ? ' active' : '')">
        <div class="overlay"></div>
        <ul>
          <li>
            <nuxt-link to="/trabajos">Trabajos</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/servicios">Servicios</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/nosotros">Nosotros</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/blog">Blog</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contacto">Contacto</nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
  export default {
    data() {
      return {
    	  menuActivo: false
      }
    },
    methods: {
      openMenu: function () {
        this.menuActivo = !this.menuActivo
      },
      closeMenu: function (event) {
        this.menuActivo = false
      },
    }
  }
</script>