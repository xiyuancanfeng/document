<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  // components: {
  //   GithubDB : require(githubDB).default
  // },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}

console.info(1)
const DB = require('../db')
console.log(DB)

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
</style>
