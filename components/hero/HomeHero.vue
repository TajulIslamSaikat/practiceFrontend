<template>
  <div class="w-full h-auto grid grid-cols-1 md:grid-cols-2 gap-y-2 justify-items-stretch px-10 py-10 bg-primary font-solaiman text-white">
    <!-- first part start -->
    <div class="flex flex-col items-center md:items-end justify-center px-4 md:px-0">
      <!-- header start -->
      <div class="text-4xl tracking-wider mb-5">
        <h1 class="font-thin">শিশুর মুখে হাসি ফুটবেই</h1>
      </div>
      <!-- header end -->

      <!-- description start -->
      <div class="text-xl tracking-wider mb-12">
        <h4 class="font-thin"><span class="block">শিশুর আত্ম-উন্নয়নের সুযোগ তৈরির মাধ্যমে</span>শিশু অধিকার প্রতিষ্ঠা করা</h4>
      </div>
      <!-- description end -->

      <!-- buttons start -->
      <div class="flex flex-col items-center justify-center md:flex-row space-y-6 md:space-y-0">
        <!-- first button -->
        <div>
          <button class="button-home"> উদ্দেশ্য </button>
        </div>
        <!-- second button -->
        <div>
          <button class="button-home"> শিখুন </button>
        </div>

      </div>
      <!-- buttons start -->
    </div>
    <!-- first part end -->

    <!-- second part (notice board) start -->
    <div class="justify-self-center w-full hidden md:block">
      <div
        class="h-96 bg-no-repeat bg-center bg-contain flex flex-col justify-center items-center"
        :style="image"
      >

        <div>
          <h1 class="text-3xl mb-4">নোটিশ</h1>
        </div>
        <div>
          <ul>
            <li>পবিত্র ঈদের ছুটি ১২ এপ্রিল</li>
            <li>পবিত্র ঈদের ছুটি ১২ এপ্রিল</li>
            <li>পবিত্র ঈদের ছুটি ১২ এপ্রিল</li>
            <li>পবিত্র ঈদের ছুটি ১২ এপ্রিল</li>
          </ul>
        </div>

      </div>
    </div>
    <!-- second part (notice board) end -->
  </div>
</template>

<script>
import backgroundHero from 'assets/svg/notish-01.svg'

export default {
  data() {
    return {
      image: { backgroundImage: `url(${backgroundHero})` },
    }
  },
}
</script>

<style scoped>
</style>