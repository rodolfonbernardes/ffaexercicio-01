<template>
  <div class="navegation">
    <h3>{{ msg }}</h3>
    <ul>
      <li><a href="#">Core Docs</a></li>
      <li><a href="#">Forum</a></li>
      <li><a href="#">Community Chat</a></li>
      <li><a href="#">Twitter</a></li>
      <li><a href="#">News</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Navegation',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.navegation li{
  list-style: none;
  display: inline-block;
  padding: 0 5px;
}
.navegation li a{
    text-decoration: none;
    font-weight: bold;
}
</style>
