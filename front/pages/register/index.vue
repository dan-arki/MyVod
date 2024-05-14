<template>
  <section class="min-h-screen flex justify-center items-center">
    <div
      class="w-full max-w-sm flex flex-col justify-center items-center gap-6"
    >
      <img src="/logoMyVod.svg" alt="" />
      <div class="bg-white p-8 w-full rounded-2xl shadow-xl">
        <p class="text-gray-900 text-center text-3xl font-bold mb-6">
          Inscription
        </p>
        <form @submit.prevent="login" class="w-full">
          <input
            class="w-full mb-5 p-3 border border-gray-300 rounded-2xl text-gray-700"
            v-model="username"
            type="text"
            placeholder="Pseudo"
            aria-label="pesudo"
          />
          <input
            class="w-full mb-5 p-3 border border-gray-300 rounded-2xl text-gray-700"
            v-model="password"
            type="email"
            placeholder="Email"
            aria-label="email"
          />
          <input
            class="w-full mb-5 p-3 border border-gray-300 rounded-2xl text-gray-700"
            v-model="password"
            type="password"
            placeholder="Password"
            aria-label="Password"
          />
          <div class="flex-col justify-center items-center gap-2">
            <p class="text-center text-xl font-semibold">Vos Plateformes</p>
            <div class="flex justify-center items-center gap-2">
              <img class="platform" src="/logoMyVod.svg" alt="" />
              <img class="platform" src="/logoMyVod.svg" alt="" />
            </div>
          </div>

          <!-- Bouton Primaire component -->
          <UiBtnPrimary :btnText="'Commencer'"></UiBtnPrimary>
        </form>
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
