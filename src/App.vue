<template>
 <p>voila</p>
</template>
<script>
export default {
  setup() {
    console.log('will be called at first')
  },
  created() {
    console.log('will be called second')
  },
  mounted() {
    console.log('will be called third')
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
