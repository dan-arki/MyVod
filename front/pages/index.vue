<template>
  <section class="min-h-screen flex flex-col justify-start gap-8">
    <UiSlider></UiSlider>
    <UiSearchBar class="mt-4"></UiSearchBar>
    <!-- Listes nouveautés -->
    <article class="mx-10">
      <UiPostersList></UiPostersList>
    </article>
    <!-- Listes plus populaires -->
    <article class="mx-10">
      <UiPostersList></UiPostersList>
    </article>

    <!-- Liste trailers -->
    <article class="flex flex-col gap-8 mx-10 mt-16">
      <h2 class="font-semibold text-5xl self-center text-white">Trailers</h2>
      <UiTrailersList></UiTrailersList>
    </article>

    <!-- Liste Autres plateformes -->
    <article class="flex flex-col gap-8 mx-10 mt-16">
      <h2 class="font-semibold text-5xl self-center text-white">
        Découvrez d’autres plateformes
      </h2>
      <UiPlatformsList></UiPlatformsList>
    </article>
  </section>
</template>
