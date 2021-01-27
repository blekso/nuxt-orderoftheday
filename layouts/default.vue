<template>
  <div>
    <Nav :index-page="isIndexPage" />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
export default {
  computed: {
    isIndexPage() {
      return this.$nuxt.$route.path === "/";
    }
  }
};
</script>

<style>
html {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  box-sizing: border-box;
}
</style>
