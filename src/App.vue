<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <UserListPage />
  </div>
</template>

<script>
import UserListPage from './components/UserListPage.vue'

export default {
  name: 'app',
  components: {
    UserListPage
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
