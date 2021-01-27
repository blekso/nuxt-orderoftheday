<template>
  <div>
    <SmallHero title="About me" />
    <TextImage
      description="Hi my name is Mihael and I study computer science at FERIT in
        Osijek, Croatia. OrderOfTheDay is project I've made in order to keep
        track of my daily To-Do's. I'm mostly interested in web projects and
        frameworks like Nuxt and React."
      image="/png/ferit.png"
    />
    <Content
      title="Need help with app?"
      description="If You need help with app, use this information to contact me directly:"
    />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "OrderOfTheDay - Contact"
    };
  }
};
</script>

<style></style>
