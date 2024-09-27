<template>

  <!-- <img alt="logo" class="logo" src="./assets/electron.svg" />
  <div class="creator">Powered by electron-vite</div>
  <div class="text">
    Build an Electron app with
    <span class="vue">Vue</span>
    and
    <span class="ts">TypeScript</span>
  </div>
  <p class="tip">Please try pressing <code>F12</code> to open the devTool</p> -->

  <div class="sidenav">


    <a href="#">
      <Button_logo />
    </a><a href="#">链接</a>
    <a href="#">链接</a>
    <a href="#">链接</a><a href="#">链接</a>
    <a href="#">链接</a>
    <a href="#">链接</a>
  </div>

  <div class="content">

    <div class="topnav">
      <a href="#">链接</a>
      <a href="#">链接</a>
      <a href="#">链接</a>

    </div>

    <div class="contentBody">
      <Button_logo />
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
      <h2>CSS 模板</h2>
      <p>顶部导航、内容和页脚。</p>
    </div>
  </div>

</template>

<script>
import Button_logo from './components/Button_logo.vue';
</script>

<style>
@import url(./assets/base.css);
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  overflow-x: hidden;
}

/* 样式侧边导航 */
.sidenav {
  width: 65px;
  height: 100%;
  position: fixed;
  z-index: 1;
}


/* 侧面导航链接 */
.sidenav a {
  color: white;
  padding: 16px;
  text-decoration: none;
  display: block;
}

/* 悬停时改变颜色 */
.sidenav a:hover {
  background-color: #ddd;
  color: black;
}


/* 样式化内容 */
.content {
  height: 100%;
  margin-left: 65px;
  background-color: #ddd;
  overflow: scroll;
}

.contentBody {
  margin-top: 50px;
}

/* 样式化顶部导航栏 */
.topnav {
  width: 100%;
    /* padding-right: 100px; */
    position: fixed;
    float: right;
    display: flex;
    justify-content: space-evenly;
    z-index: 9999;
    background-color: #33333349;
    align-content: center;
    align-items: center;
}



/* 设置顶部导航链接的样式 */
.topnav a {
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  
}

/* 悬停时改变颜色 */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}



</style>