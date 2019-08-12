<template>
  <div class="home">
    <img alt="Our logo" src="../assets/오구2.jpg" margin-top="10px;" width="600" height="500"> 
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'home',
  components: {
    HelloWorld,
  }
}
</script>

<style>
.home {
  margin-top: 50px;
}
</style>