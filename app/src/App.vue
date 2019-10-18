<template>
  <div id="app">
    这里是git测试
    <!-- lry -->
    <div>这里是路人乙的注册</div>
    <!-- 这里是路人甲 -->
    <Login></Login>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Login from './components/Login'
export default {
  name: 'app',
  components: {
    HelloWorld,
    Login
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
  margin-top: 60px;
}
</style>
