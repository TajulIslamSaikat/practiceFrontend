<template>
  <div>
      <NavBar />
      <Nuxt />
      <FooterBar />
  </div>
</template>

<script>
import NavBar from '@/components/header/NavBar.vue';
import FooterBar from '@/components/footer/FooterBar.vue';

export default {
 components: {
     NavBar,
     FooterBar
 },
}

</script>