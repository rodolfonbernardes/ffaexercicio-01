<template>
  <div id="app">
    <Header msg="Welcome to Your Vue.js App"/>
    <Navegation msg="Essential Links"/>
    <Articles msg="For a guide and recipes pn how to configure / customize this project"/>
    <Sidebar msg="Mais Posts"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navegation from './components/Navegation.vue'
import Articles from './components/Articles.vue'
import Sidebar from './components/SideBar.vue'

export default {
  name: 'App',
  components: {
    Header,
    Navegation,
    Articles,
    Sidebar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
