<template>
  <header className="App-header">
    <h1>🛥️</h1>
    <h4>Keeping it classy since 2021</h4>
  </header>
  <div id="main">
    <div class="card">
      <h3>T-Shirt</h3>
    </div>
    <div class="card">
      <h3>Hat</h3>
    </div>
    <div class="card">
      <h3>T-Shirt</h3>
    </div>
    <div class="card">
      <h3>Hat</h3>
    </div>
  </div>

  <footer>
    <p>&copy; {{ date }} EPYC</p>
  </footer>
</template>

<script>
export default {
  name: "HelloWorld",
  data: function() {
    return {
      date: new Date().getFullYear()
    };
  },
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
