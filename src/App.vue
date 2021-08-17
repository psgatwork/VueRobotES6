<template>
  <main>
    <HomePage />
  </main>
</template>

<script>
import HomePage from "./components/HomePage.vue";

export default {
  name: "App",
  components: {
    HomePage,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, rgb(37, 51, 243), rgb(29, 245, 83));
  background-attachment: fixed;
}

#app {
  font-family: segoe ui light;
}

main {
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width: 1024px;
  min-height: 30px;
}
</style>
