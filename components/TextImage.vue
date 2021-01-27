<template>
  <div class="grid md:grid-cols-2 grid-cols-1">
    <div v-if="!textLeft" class="flex items-center justify-center py-8">
      <img :src="image" class="w-2/5 rounded-lg" />
    </div>
    <div class="flex flex-col items-center justify-center p-8">
      <h4 class="sm:text-3xl text-2xl">{{ title }}</h4>
      <p class="sm:text-xl text-lg">{{ description }}</p>
    </div>
    <div v-if="textLeft" class="flex items-center justify-center py-8">
      <img :src="image" class="w-2/5 rounded-lg" />
    </div>
  </div>
</template>

<script>
export default {
  props: {
    textLeft: {
      type: Boolean,
      default: true
    },
    title: {
      type: String,
      default: ""
    },
    description: {
      type: String,
      default: ""
    },
    image: {
      type: String,
      default: "/png/phone.png"
    }
  }
};
</script>

<style></style>
