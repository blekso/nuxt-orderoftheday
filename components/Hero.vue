<template>
  <div
    class="flex flex-col justify-center items-center md:h-75vh bg-blue-800 md:p-40 p-4"
  >
    <span class="font-billabong text-6xl text-white">{{ title }}</span>
    <p class="text-white">{{ description }}</p>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: ""
    },
    description: {
      type: String,
      default: ""
    }
  }
};
</script>

<style></style>
