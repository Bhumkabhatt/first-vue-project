<template>
  <button @click="count++">
    Count is: {{ count }}
  </button>
</template>

<script>
export default {
  name: 'App',
  components: {
    
  },
  data() {
    return {
      count: 0
    }
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
  margin-top: 60px;
}
</style>
