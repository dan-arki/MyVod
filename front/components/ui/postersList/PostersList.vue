<template>
  <div class="flex flex-col gap-4">
    <h3 class="font-bold text-lg">{{ titleText }}</h3>
    <UiPosterCard></UiPosterCard>
  </div>
</template>

<script>
export default {
  props: {
    titleText: {
      type: String,
      default: "Nouveautés",
    },
  },
};
</script>
