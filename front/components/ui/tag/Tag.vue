<template>
  <div
    class="flex items-center justify-center px-7 py-3 rounded-full bg-blue400 bg-opacity-10 transition ease-in-out duration-300"
  >
    <span class="text-base text-blue400 text-center">{{ tagText }}</span>
  </div>
</template>

<script>
export default {
  props: {
    tagText: {
      type: String,
      default: "Films",
    },
  },
};
</script>
