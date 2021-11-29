<template>
  <div class="bg-graphite-800 p-4 text-gray-50 text-xl">
    <Lorem />
  </div>
</template>

<script>
import Lorem from '../components/lorem.vue'

export default {
  components: {
    Lorem
  },
  layout () {
    return 'default'
  }
}
</script>
