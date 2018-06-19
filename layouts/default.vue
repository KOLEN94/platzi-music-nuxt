<template lang="pug">
  div
    pm-header
    nuxt
    pm-footer
</template>
<script>
  import pmHeader from '~/components/Header.vue'
  import pmFooter from '~/components/Footer.vue'
  export default {
    components: { pmHeader, pmFooter }
  }
</script>
