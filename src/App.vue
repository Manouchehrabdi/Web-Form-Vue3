<template>
  <h1
    class="text-blue-600/100 dark:text-sky-400/100 text-center font-bold text-2xl mt-6"
  >
    SignUp Welcome
  </h1>
  <SignupForm />
</template>

<script>
import SignupForm from "./components/SignupForm.vue";
export default {
  name: "App",
  components: { SignupForm },
};
</script>
