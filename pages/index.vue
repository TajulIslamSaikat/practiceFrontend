<template>
  <div class="w-full">
    <HomeHero />
    <HomeProgress />
    <HomeProkolpo />
    <HomeClub />
    <HomeGallery />
    <HomeDonorboard />
  </div>
</template>

<script>
import HomeHero from '@/components/hero/HomeHero.vue'
import HomeProgress from '@/components/progress/HomeProgress.vue'
import HomeProkolpo from '@/components/prokolpo/HomeProkolpo.vue'
import HomeClub from '@/components/club/HomeClub.vue'
import HomeGallery from '@/components/gallery/HomeGallery.vue'
import HomeDonorboard from '@/components/donorboard/HomeDonorboard.vue'

export default {
  components: {
    HomeHero,
    HomeProgress,
    HomeProkolpo,
    HomeClub,
    HomeGallery,
    HomeDonorboard,
  },
}
</script>
