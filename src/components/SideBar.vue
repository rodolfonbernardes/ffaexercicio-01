<template>
  <div class="sidebar">
    <h3>{{ msg }}</h3>
    <ul>
      <li>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's...</p>        
      </li>
      <li>
        <p>My content My content My content My content My content My content My content My content My content My content My content My content My content My content My content</p>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
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
  display: block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.sidebar{
    width: 20%;
    padding:0 5%;
    display:inline-block;
  }
</style>
