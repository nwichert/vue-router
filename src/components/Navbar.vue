<template>
  <nav class="main-nav">
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link :to="{ name: 'About' }">About</router-link></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {

    }
  }
}
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
