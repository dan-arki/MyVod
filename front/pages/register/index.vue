<template>
  <section class="min-h-screen flex justify-center items-center">
    <div
      class="w-full max-w-sm flex flex-col justify-center items-center gap-6"
    >
      <NuxtLink to="/">
        <img src="/logoMyVod.svg" alt="" />
      </NuxtLink>
      <div class="bg-white p-8 w-full rounded-2xl shadow-xl">
        <p class="text-gray-900 text-center text-3xl font-bold mb-6">
          Inscription
        </p>
        <form @submit.prevent="login" class="w-full">
          <input
            class="w-full mb-5 p-3 border bg-white border-gray-300 rounded-2xl text-gray-700"
            v-model="username"
            type="text"
            placeholder="Pseudo"
            aria-label="pesudo"
          />
          <input
            class="w-full mb-5 p-3 border bg-white border-gray-300 rounded-2xl text-gray-700"
            v-model="password"
            type="email"
            placeholder="Email"
            aria-label="email"
          />
          <input
            class="w-full mb-5 p-3 border bg-white border-gray-300 rounded-2xl text-gray-700"
            v-model="password"
            type="password"
            placeholder="Password"
            aria-label="Password"
          />
          <div class="flex-col justify-center items-center gap-2">
            <p class="text-center text-xl font-bold text-textBlack">
              Vos Plateformes
            </p>
            <div class="flex justify-center items-center gap-2">
              <img class="platform" src="/logoMyVod.svg" alt="" />
              <img class="platform" src="/logoMyVod.svg" alt="" />
            </div>
          </div>

          <!-- Primary Button component -->
          <UiBtnPrimary :btnText="'Commencer'"></UiBtnPrimary>
        </form>
        <div class="flex gap-1 justify-center mt-5">
          <span class="font-bold text-xs text-textBlack">Déjà un compte ?</span>
          <NuxtLink to="/login" class="text-blue400 font-bold text-xs"
            >Se connecter</NuxtLink
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      username: "",
      password: "",
    };
  },
  methods: {
    login() {
      console.log("Login attempt with", this.username, this.password);
    },
  },
};
</script>

<style scoped>
.platform {
  width: 70px;
  height: 70px;
}
</style>
