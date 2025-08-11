<template>
  <div class="page-outer">
    <div class="page-inner">
      <div class="home1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/02d8d421f41f688bd08ec969df4a4fa0.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/80916efff50be1945c152692aadcf87c.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/b62056ff7a67c3c6721dd9bb2ab5cf01.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/a66f68e2cf2fcf9061fabff0d04fd3c5.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/167afaf1a3a5aa758377d182227089d4.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="./assets/5.gif">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/679761809df713a6675d12eb9419a643.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/48ba889c369c98ce1dc56bae5d0eee14.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/2c096f58970e705fbe52925e906f2e7e.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/373a41aaee32da4900c7e8b2d1ee8066.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/eb9ed736f55e2e6aa3734827cbe6e40f.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/10b4ad1de94091596b145273cb734e39.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/90b88e99e49e7226e3d8f742c5bf346d.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <video controls class="video">
          <source src="https://hf.max-c.com/file/1954892945874362368.mp4" type="video/mp4">
        </video>
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/7f8665892581576d116cf23511acda61.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/ed1daf4f4da75d0a461704e76f95bfb9.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/9bbefb568049eefdb3868cc69e75a28d.png?imageMogr2/format/webp/quality/40/ignore-error/1">
        <img src="https://imgheybox.max-c.com/web/bbs/2025/08/11/416e0f1d99c3dabdca35de033ce6d875.png?imageMogr2/format/webp/quality/40/ignore-error/1">
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
