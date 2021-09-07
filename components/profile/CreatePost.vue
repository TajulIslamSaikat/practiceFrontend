<template>
  <div class="px-2 py-10 font-solaiman">
    <!-- header start -->
    <div class="flex flex-row gap-x-3">
      <!-- profile img start -->
      <div class="w-2/12 md:w-1/12">
        <img
          src="/logost.png"
          alt=""
          class=""
        >
      </div>
      <!-- profile img end -->
      <!-- post form start -->
      <div class="w-10/12 md:w-11/12">
        <form
          action=""
          class="w-full"
        >
          <div class="flex flex-col">
            <!-- textarea start -->
            <div>
              <textarea
                class="appearance-none block w-full px-3 py-2 border border-gray-200 rounded leading-tight focus:outline-none focus:border-main"
                name="postDescription"
                id="txt"
                rows="4"
              ></textarea>
            </div>
            <!-- textarea end -->
            <!-- buttons start -->
            <div class="flex flex-row flex-wrap">
              <!-- input image file start -->
              <div class="w-1/2 py-4">
                <div class="flex flex-wrap gap-3 justify-start">
                  <div class="w-8">
                    <img src="https://img.icons8.com/ios-filled/50/000000/video.png" />
                  </div>
                  <div class="w-8">
                    <img src="https://img.icons8.com/ios-filled/50/000000/image.png" />
                  </div>
                  <div class="w-8">
                    <img src="https://img.icons8.com/ios-filled/50/000000/file.png" />
                  </div>

                </div>
              </div>
              <!-- input image file end -->
              <!-- category and post start -->
              <div class="w-1/2 py-4">
                <div class="flex flex-wrap gap-2 justify-end">
                  <!-- category button start -->
                  <div>
                    <button
                      class="shadow bg-main hover:bg-primary focus:shadow-outline focus:outline-none text-white text-xs md:text-sm lg:text-lg py-1 px-2 rounded"
                      type="button"
                    >Category</button>
                  </div>
                  <!-- category buttonj end -->
                  <!-- post button start -->
                  <div>
                    <button
                      class="shadow bg-main hover:bg-primary focus:shadow-outline focus:outline-none text-white text-xs md:text-sm lg:text-lg py-1 px-2 rounded"
                      type="button"
                    >Post</button>
                  </div>
                  <!-- post button end -->
                </div>
              </div>
              <!-- category and post end -->
            </div>
            <!-- button end -->
          </div>

        </form>
      </div>
      <!-- post form end -->
    </div>
    <!-- header end -->
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
</style>