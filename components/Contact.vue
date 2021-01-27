<template>
  <div class="grid md:grid-cols-3 grid-cols-1 h-75vh">
    <div class="flex flex-col justify-center items-center col-span-2">
      <div class="heading text-center font-bold text-2xl m-5 text-gray-800">
        Need help with App? Contact me here:
      </div>
      <div
        class="editor mx-auto w-10/12 flex flex-col text-gray-800 border border-gray-300 p-4 shadow-lg max-w-2xl"
      >
        <input
          class="title bg-gray-100 border border-gray-300 p-2 mb-4 outline-none"
          spellcheck="false"
          placeholder="Title"
          type="text"
        />
        <textarea
          class="description bg-gray-100 sec p-3 h-60 border border-gray-300 outline-none"
          spellcheck="false"
          placeholder="Describe everything about this mail here"
        ></textarea>

        <a
          href="mailto:abc@example.com?subject = Feedback&body = Message"
          class="w-1/6 mt-8"
        >
          <div
            class="btn border border-indigo-500 p-1 px-4 font-semibold cursor-pointer text-gray-200 ml-2 bg-indigo-500"
          >
            Send
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
