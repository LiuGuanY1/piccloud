<script setup>
import { RouterView } from 'vue-router'

import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.bundle.min.js'
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-dark navbar-dark fixed-top">
    <div class="container">
      <img src="./components/icons/3.jpg" alt="logo" class="smaller-img">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navmenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="/" title="首页">首页</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/about" title="下载">下载</a>
          </li>
          <li class="nav-item">
            <a class="nav-link"
              href="http://static-mp-52a185d0-9d2e-4968-af9b-07db381d8ec8.next.bspapp.com//piccloud/index.html#"
              title="登录/注册">登录/注册</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <RouterView />
</template>

<style scoped>
.smaller-img {
  width: 200px;
  /* 设置固定宽度 */
  height: auto;
}
</style>
