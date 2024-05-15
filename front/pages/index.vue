<template>
  <section class="min-h-screen flex flex-col justify-start gap-8">
    <UiSlider></UiSlider>
    <UiSearchBar></UiSearchBar>
    <!-- Listes nouveautés -->
    <article class="mx-10">
      <UiPostersList></UiPostersList>
    </article>
    <!-- Listes plus populaires -->
    <article class="mx-10">
      <UiPostersList></UiPostersList>
    </article>

    <!-- Liste trailers -->
    <article class="flex flex-col gap-8 mx-10">
      <h2 class="font-semibold text-5xl self-center text-white">Trailers</h2>
      <UiTrailersList></UiTrailersList>
    </article>
  </section>
</template>
