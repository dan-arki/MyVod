<template>
  <!-- header -->
  <header class="flex justify-between w-full items-center px-8 py-2 mt-2">
    <div>
      <img class="w-28 h-28" src="/logoMyVod.svg" alt="logo" to="/" />
    </div>
    <nav>
      <ul class="flex gap-6">
        <li class="flex flex-col items-center">
          <img src="/watchings.svg" alt="" />
          <nuxt-link
            class="text-white text-lg hover:text-blue400 hover:font-semibold transition duration-300 ease-in-out"
            >Déjà vu</nuxt-link
          >
        </li>
        <li class="flex flex-col items-center">
          <img src="/watchlist.svg" alt="" />
          <nuxt-link
            class="text-white text-lg hover:text-blue400 hover:font-semibold transition duration-300 ease-in-out"
            >Watchlist</nuxt-link
          >
        </li>
      </ul>
    </nav>

    <div>
      <UiBtnPrimary
        :btnText="'Commencer'"
        size="large"
        to="/register"
      ></UiBtnPrimary>
    </div>
  </header>
</template>
