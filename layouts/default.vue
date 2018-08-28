<template>
  <div>
    <TopWave/>
    <Top/>
    <nuxt/>
    <Foot/>
  </div>
</template>

<script>
  import TopWave from '~/components/TopWave.vue'
  import Top from '~/components/Top.vue'
  import Foot from '~/components/Foot.vue'

  export default {
    components: {
      TopWave,
      Top,
      Foot
    }
  }
</script>
