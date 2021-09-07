<template>
  <div class="bg-gray-100 font-solaiman text-main">
    <div class="container mx-auto min-h-screen py-10 flex flex-wrap items-center justify-center">
      <!-- logo start -->
      <div class="p-5 w-full md:w-1/2 flex justify-center">
        <img
          src="/logoft.png"
          alt=""
        >
      </div>
      <!-- logo end -->

      <!-- form start -->
      <div class="w-full md:w-1/3 bg-white p-4 mx-7 my-10 md:my-0 md:mx-0 rounded-md shadow-md">
        <div class="w-full text-center pb-5 pt-2">
          <h2 class="font-bold text-3xl">একাউন্টে প্রবেশ করুন</h2>
        </div>
        <form class="w-full">
          <div class="w-full px-3 mb-6">
            <label
              class="block capitalize tracking-wide text-md font-bold mb-2"
              for="grid-first-name"
            >
              Username/Email
            </label>
            <input
              class="appearance-none block w-full border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:border-main"
              id="grid-first-name"
              type="text"
              placeholder="shishurjonnoamra"
            >
          </div>
          <div class="w-full px-3 mb-6">
            <label
              class="block capitalize tracking-wide text-md font-bold mb-2"
              for="grid-password"
            >
              Password
            </label>
            <input
              class="appearance-none block w-full border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:border-main"
              id="grid-password"
              type="password"
              placeholder="******************"
            >
            <p class="text-red-700 text-xs">The password that you've entered is incorrect. Forgotten password?</p>
          </div>

          <div class="px-3 flex flex-col justify-center pb-5 space-y-2">
            <button
              class="shadow bg-main hover:bg-primary focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded"
              type="button"
            >
              Login
            </button>
            <a href="#">Forgotten password?</a>
          </div>
          <hr>
          <div class=" px-3 flex justify-center py-5">
            <button
              class="shadow bg-main hover:bg-primary focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded"
              type="button"
            >
              Create Donor Account
            </button>
          </div>
        </form>
        <div class="w-full text-center">
          <a
            href="#"
            class="text-md hover:text-primary"
          >মূল পাতায় ফিরে যান</a>
        </div>
      </div>
      <!-- form end -->
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
</style>