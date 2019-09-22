<template>
  <div class="home">
  <span class='message'>AzureGap</span>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home > img {
  height: 20px;;
}

.message {
  font-size: 80px;
}
</style>