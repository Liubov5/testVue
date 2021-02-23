<template>
  <Menu msg="LIUBA" />
  <router-view/>
</template>

<script>
//подключаю компонент
import Menu from '@/components/menu.vue'

//регистрирую компонент, чтобы дальше его использовать
export default{
  components: {
    Menu
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
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
