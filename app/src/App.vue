<template>
  <div id="app">
    这里是git测试
    <!-- lry -->
    <div>这里是路人乙的注册</div>
    <!-- 这里是路人甲 -->
    <h1>现在是北京时间2019年10月18日20:46:41</h1>
    <strong>入侵者：纪晨曦</strong>
    <h2>小芳到小王晗的远程仓库到此一游</h2>
    <h3>今天我俩斥巨资买了一个服务器</h3>
    <h4>此时此刻我俩的身份地位已经截然不同了</h4>
    <h5>霸屏结束，overover</h5>
    <h6>北京时间2019年10月19日10:42:28小芳留</h6>
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
  strong{
    font-size: 100px;
    color: red;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
