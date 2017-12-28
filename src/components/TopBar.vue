<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <h2>Top bar work pls</h2>
  </div>
</template>

<script>
export default {
  name: 'TopBar',
  data() {
    return {
      msg: 'Jason Groff',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
.main {
  background-color: gray;
}
.blue {
  color: lightblue;
}
</style>
