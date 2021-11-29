<template>
  <div class="h-screen flex flex-col bg-graphite-900">
    <Header />
    <main class="flex-grow">
      <Nuxt />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from '../components/header.vue'
import Footer from '../components/footer.vue'

export default {
  components: {
    Header,
    Footer
  },
  head: {
    htmlAttrs: {
      lang: 'en'
    },
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' }
    ],
    title: 'Jon Richards'
  }
}
</script>
