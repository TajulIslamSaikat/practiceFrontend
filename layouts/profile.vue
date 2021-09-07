<template>
  <div>
    <NavBar />
    <Nuxt />
  </div>
</template>

<script>
import NavBar from '@/components/header/NavBar.vue'

export default {
  components: {
    NavBar,
  },
}
</script>