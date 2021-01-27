<template>
  <div class="flex flex-col lg:w-2/3 py-8 lg:px-40 md:px-20 px-8">
    <h4 class="sm:text-3xl text-2xl mb-8">{{ title }}</h4>
    <p class="sm:text-xl text-lg mb-8">{{ description }}</p>
    <ul>
      <li class="mb-8 text-xl">Phone: +385 1111 222</li>
      <li class="mb-8 text-xl">
        <a href="mailto:webmaster@example.com">Email: mihael.istvan@ferit.hr</a>
      </li>
    </ul>
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
