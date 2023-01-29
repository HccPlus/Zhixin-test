<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div id="top">
    <button onclick="window.location.href='../../src/Login/index.html'">登录</button>
    <div class="divide">|</div>
    <button onclick="window.location.href='../../src/Signup/index.html'">注册</button>
  </div>
  <div id="tab">
    <h1>测试页面</h1>
    <h2>CE SHI YE MIAN</h2>
  </div>
  <ul id="nav">
    <li>
      <a href="https://baidu.com">百度</a>
    </li>
    <li>
      <a href="https://jd.com">京东</a>
    </li>
    <li>
      <a href="https://mi.com">小米</a>
    </li>
    <li>
      <a href="https://taobao.com">淘宝</a>
    </li>
  </ul>
  <HelloWorld />

</template>

<style scoped>

</style>
