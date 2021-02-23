<template>
    <a href="/">Main page</a>
    <a href="/about">About</a>
    <a href="/menu1">Menu 1</a>
    <p>{{msg}}</p>
</template>
<script>
export default {
name: 'Menu',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">

a {
  color: #42b983;
  margin-left: 30px;
}
</style>
