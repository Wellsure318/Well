<template>
  <div class="page-outer">
    <div class="page-inner">
      <div class="home1">
        <img src="./assets/1.png">
        <img src="./assets/2.png">
        <img src="./assets/3.png">
        <img src="./assets/4.png">
        <img src="./assets/5.png">
        <img src="./assets/5.gif">
        <img src="./assets/6.png">
        <img src="./assets/7.png">
        <img src="./assets/8.png">
        <img src="./assets/9.png">
        <img src="./assets/10.png">
        <img src="./assets/11.png">
        <img src="./assets/12.png">
        <video controls class="video">
          <source src="./assets/骨骼绑定演示视频.mp4" type="video/mp4">
        </video>
        <img src="./assets/13.png">
        <img src="./assets/14.png">
        <img src="./assets/15.png">
        <img src="./assets/16.png">
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.page-outer {
  min-height: 100vh;
  background-color: white; /* 整个页面白色背景 */
  display: flex;
  justify-content: center; /* 水平居中内层容器 */
  align-items: flex-start;
  padding: 20px 0; /* 上下留20px空隙 */
  box-sizing: border-box;
}

.page-inner {
  width: 90vw;       /* 页面宽度的90% */
  max-width: 1200px; /* 最大宽度 */
  
  /* 格子背景 */
  background-color: white;
  background-image:
    linear-gradient(to right, #ccc 1px, transparent 1px),
    linear-gradient(to bottom, #ccc 1px, transparent 1px);
  background-size: 30px 30px;
  
  padding: 24px 40px; /* 内边距让内容不贴边 */
  box-sizing: border-box;
  box-shadow: 0 6px 15px rgba(0,0,0,0.05);
}

.home1 img {
  margin: 20px 0; /* 图片间距 */
}

.video {
  max-width: 100%;   /* 最多和容器一样宽 */
  height: auto;      /* 按比例缩放 */
  margin: 20px 0;    /* 上下间距 */
}

.home1 {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.home1 img {
  max-width: 100%;
  height: auto;
  display: block;
}
</style>
