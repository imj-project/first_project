<template>
  <div id="app">
    <Header></Header>
    <p>숨은 밍구 찾기</p>
    <strong>오구 오구 오구 오구 오구 오구 밍구 오구 오구</strong>
    <router-view/>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'app',
  components: {
    Header,
    Footer,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 20px;
}
</style>
