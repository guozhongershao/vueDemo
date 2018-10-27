<!-- 1. 模板 : html 结构-->
<template>
  <!-- 有且只能由一个跟标签 -->
  <div id="app">
    <h1>{{title}}</h1>
    <app-header></app-header>
    <users></users>
  </div>
</template>

<!-- 2. 行为：处理逻辑-->
<script>
  import Users from "./components/Users"
  import Header from './components/Header'

  export default {
    name: 'App',
    data(){
      return {
        title : '这是我的第一个Vue脚手架项目'
      }
    },
    // 局部注册组件
    components:{
      "users": Users,
      "app-header": Header
    }
  }
</script>

<!-- 3. 样式：解决样式-->
<style>
h1 {
  color: purple;
}
</style>
