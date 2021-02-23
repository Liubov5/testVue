<template>
  <div class="">
      <h2>{{ title }}</h2>
      <p v-if="inStock">В продаже</p>
      <p v-else>Товар закончился</p>
  </div>
</template>

<script>
export default {
  name: 'Description',
  props: {
    msg: String
  },
  data(){
    return{
       title:"Socks",
       inStock:true,
    }
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
