<template>
  <div class="flex justify-between items-center h-16 lg:px-20 px-4">
    <nuxt-link to="/">
      <div class="flex items-center justify-center">
        <img src="/png/logo.png" class="w-8 h-8 mr-4" />
        <h3 class="font-billabong lg:text-4xl text-2xl">OrderOfTheDay</h3>
      </div>
    </nuxt-link>
    <ul class="flex">
      <a href="/" class="flex justify-center items-center hover:underline"
        ><li
          class="lg:mr-4 mr-2"
          :class="{ 'rounded-lg bg-gray-500 px-4 py-2 text-white': indexPage }"
        >
          Home
        </li></a
      >
      <a
        href="/contact"
        class="flex justify-center items-center hover:underline"
        ><li
          class="lg:mr-4 mr-2"
          :class="{ 'rounded-lg bg-gray-500 px-4 py-2 text-white': !indexPage }"
        >
          Contact
        </li></a
      >
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    indexPage: {
      type: Boolean,
      default: ""
    }
  }
};
</script>

<style></style>
