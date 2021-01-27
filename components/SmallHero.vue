<template>
  <div
    class="flex justify-start items-center h-third bg-blue-800 md:p-40 px-10"
  >
    <span class="text-6xl text-white">{{ title }}</span>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: ""
    }
  }
};
</script>

<style></style>
