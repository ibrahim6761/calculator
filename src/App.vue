<template>
  <div id="app">
    <hesapMakinesi></hesapMakinesi>
  </div>
</template>

<script>
import hesapMakinesi from "@/components/hesapMakinesi";

export default {
  name: 'App',
  components: {
    hesapMakinesi : hesapMakinesi
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
