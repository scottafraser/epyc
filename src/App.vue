<template>
  <div id="nav">
    <button>
      <h1>Join the club</h1>
    </button>
  </div>
  <img alt="Vue logo" src="./assets/logo.jpg" />
  <Main msg="Welcome to Your Vue.js App" />
</template>

<script>
import Main from "./components/Main.vue";

export default {
  name: "App",
  components: {
    Main
  }
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

#nav {
  width: 99vw;
  display: flex;
  justify-content: flex-end;
}

button {
  border: none;
  padding: 1em 2em;
  border-radius: 20px;
}
button h1 {
  padding: none;
}

img {
  max-width: 90vw;
  padding: 2em;
}
</style>
