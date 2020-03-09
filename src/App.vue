<template>
  <div id="app">
    <Header/>
    <Posts/>
  </div>
</template>

<script>
import Posts from './components/Posts'
import Header from './components/Header'
export default {
  name: 'App',
  components: {
    Header,
    Posts
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.wrapper {
  max-width: 1020px;
  margin: 0 auto;
}
</style>
