<template>
  <div id="app">
    <Header Msg="Exercício 01 - Vue"/>
  </div>
</template>

<script>
   import Header from './components/Header.vue';

    export default {
        name: 'App',
        components: {
            Header,
        },
        data() {
            return {
                arrMenu: [
                    { id: 1, item: "Home"},
                    { id: 2, item: "Sobre"},
                    { id: 3, item: "Contato"},
                ]
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
