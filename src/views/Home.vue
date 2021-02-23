<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <hello-world/>
    <div class="col-8 mx-auto bg-danger p-3">
      <div class="row">
        <div class="col-6">
          <Image :address="require('../assets/socks_blue.jpg')"/>
        </div>
        <div class="col-6">
         <Description />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

import Image from '@/components/image.vue'
import Description from '@/components/Description.vue'

export default {
  name: 'Home',
  components: {  
    Image,
    Description
  }
}
</script>
<style scoped lang="scss">

</style>
