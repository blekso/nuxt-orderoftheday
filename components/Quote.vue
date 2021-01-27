<template>
  <div class="flex flex-col justify-center lg:px-40 md:px-20 p-4">
    <div>
      <span class="font-billabong lg:text-6xl text-3xl">"{{ quote }}"</span>
      <span>- {{ author }}</span>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    quote: {
      type: String,
      default: ""
    },
    author: {
      type: String,
      default: ""
    }
  }
};
</script>

<style></style>
