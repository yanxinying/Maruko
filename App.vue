<!-- 展示模板 -->
<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <!-- 这里写的是文件的名称 -->
    <p>--------------我是华丽丽的分割线--------------</p>
    <forms></forms>
    <p>--------------我是华丽丽的分割线--------------</p>
    <onClick></onClick>
    <p>--------------我是华丽丽的分割线--------------</p>
    <bindingClass></bindingClass>
    <p>--------------我是华丽丽的分割线--------------</p>
    <calculation></calculation>
    <p>--------------我是华丽丽的分割线--------------</p>
    <loop></loop>
    <p>--------------我是华丽丽的分割线--------------</p>
    <ifJudge></ifJudge>
    <p>--------------我是华丽丽的分割线--------------</p>
    <hello></hello>
    <!-- <router-view/> -->
  </div>
</template>

<script>
// export default {
//   name: 'app'
// }
//导入组件
import Hello from './components/Hello'
import ifJudge from './components/ifJudge'
import loop from "./components/loop.vue"
import calculation from "./components/calculation.vue"
import bindingClass from "./components/bindingClass.vue"
import onClick from "./components/onClick.vue"
import forms from "./components/forms.vue"

export default {
  name: 'app',
  components: {
    Hello,
    ifJudge,
    loop,
    calculation,
    bindingClass,
    onClick,
    forms
  }
}
</script>
<!-- 样式代码 -->
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
