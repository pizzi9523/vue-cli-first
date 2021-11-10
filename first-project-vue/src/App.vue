<template>
  <div id="app">
    <Title />
  </div>
</template>

<script>
import Title from "./components/Title.vue";

export default {
  name: "App",
  components: {
    Title,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
