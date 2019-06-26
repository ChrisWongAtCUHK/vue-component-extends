<template>
  <div id="app">
    <AdminListPage />
  </div>
</template>

<script>
import AdminListPage from './components/AdminListPage.vue'

export default {
  name: 'app',
  components: {
    AdminListPage
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
