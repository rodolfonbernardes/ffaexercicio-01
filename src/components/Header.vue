<template>
  <div>
    <img alt="Vue logo" src="./../assets/logo.png">
    <h1>{{Msg}}</h1>
  </div>
</template>

<script>
export default {
    name: 'Header',
    props: {
        Msg: String
    }
}
</script>

<style scoped>
    h3 {
    margin: 40px 0 0;
    }
    div {
            border-top: 10px solid #383f5d;
            background:#FFEDE1;
    }
</style>