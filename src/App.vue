<script>
import SignUp from "./components/SignUp.vue";

export default {
  name: "app",

  components: {
    SignUp,
  },
};
</script>

<template>
  <SignUp />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
</style>
