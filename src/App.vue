<template>
<div id="app">
  <!--<img src="./assets/logo.png"/>-->
   则是一个基于vue-cli搭建的，eslint规则检查是默认的，有点儿烦人，
   遗留问题是配置eslint
  <router-view/>
</div>
</template>

<script>
export default {
  name: 'App'
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
