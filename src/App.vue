<template>
  <div id="app">
    <AppHeader />
    <div id="main">
      <AppTodos />
    </div>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
import AppTodos from "./components/AppTodos.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    AppTodos,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
