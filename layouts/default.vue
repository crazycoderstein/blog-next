<template>
  <div class="min-h-screen flex flex-col bg-grey-800 font-playfair">
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
    title: 'Jon Richards',
    link: [
      { rel: 'preconnect', href: 'https://fonts.googleapis.com' },
      { rel: 'preconnect', href: 'https://fonts.gstatic.com', crossorigin: true },
      { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap' }
    ]
  }
}
</script>
