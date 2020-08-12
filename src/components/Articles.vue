<template>
  <div class="article">
    <h1>{{ msg }}</h1>
    <p>
     My content My content My content My content My content My content My content My content My content My content My content My content My content My content My content
     My content My content My content My content My content My content My content My content My content My content My content My content My content My content My content
     My content My content My content My content My content My content My content My content My content My content My content My content My content My content My content
     My content My content My content My content My content My content My content My content My content My content My content My content My content My content My content
     My content My content My content My content My content My content My content My content My content My content My content My content My content My content My content</p>
  </div>
</template>

<script>
export default {
  name: 'Articles',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.article{
  width: 30%;
  display:inline-block;
}
</style>