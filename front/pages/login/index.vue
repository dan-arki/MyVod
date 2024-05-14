<!-- <script setup>
import btnPrimary from "../../components/ui/btnPrimary";
</script> -->

<template>
  <UiHeader></UiHeader>
  <section class="min-h-screen flex justify-center items-center">
    <div
      class="w-full max-w-sm flex flex-col justify-center items-center gap-6"
    >
      <img src="/logoMyVod.svg" alt="" />
      <div class="bg-white p-8 w-full rounded-2xl shadow-xl">
        <p class="text-gray-900 text-center text-3xl font-bold mb-6">
          Connexion
        </p>
        <form @submit.prevent="login" class="w-full">
          <input
            class="w-full mb-5 p-3 border border-gray-300 rounded-2xl text-gray-700"
            v-model="username"
            type="text"
            placeholder="Pseudo"
            aria-label="Pseudo"
          />
          <input
            class="w-full mb-5 p-3 border border-gray-300 rounded-2xl text-gray-700"
            v-model="password"
            type="password"
            placeholder="Password"
            aria-label="Password"
          />
          <!-- Bouton Primaire component -->
          <UiBtnPrimary :btnText="'Continuer'" size="medium"></UiBtnPrimary>
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

<style scoped></style>
