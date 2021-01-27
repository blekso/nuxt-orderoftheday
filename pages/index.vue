<template>
  <div>
    <Hero title="OrderOfTheDay" description="To-Do's list Android App" />
    <Quote quote="Subtracting from your list of priorities is as important as adding to
        it." author="Frank Sonnenberg, Soul Food: Change Your Thinking, Change Your
        Life"/>
    <Features />
    <TextImage title="Simple design" description="Add or delete Your To-do's with easy to use and interactive layout" image="/jpg/screenshot_01.jpg"/>
    <TextImage title="Settings tab" description="Easy access to this web site and to help page" image="/jpg/screenshot_02.jpg" :text-left="false" />
    <Download />
  </div>
</template>

<script>
export default {
  head() {
      return {
        title: "OrderOfTheDay"
      }
    }
};
</script>

<style></style
Download>
