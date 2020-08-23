<template>
  <div id="app">
    <NavBar />
    <Home />
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import Home from "@/views/Home.vue";
export default {
  components: {
    NavBar,
    Home
  }
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
}
*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  box-sizing: border-box;
  font-size: 62.5%;
}

body {
  font-weight: 500;
  line-height: 1.8;
  min-height: 100vh;
}
</style>
