<template>
  <Navigation />
  <router-view />
  <Footer />
</template>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
  }
</style>

<script>
import Navigation from '@/components/Navigation.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navigation,
    Footer
  }
}
</script>
