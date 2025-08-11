<template>
  <div class="gezi">
    <div class="container">
      <section class="top-section">
        <div class="left">
          <h1 class="title">作品集</h1>
          <div class="btn-group">
            <n-button circle color="#222" size="large">联系我</n-button>
            <n-button circle color="#222" size="large">给企业的一封信</n-button>
          </div>
        </div>
        <div class="right">
          <img src="./assets/character.png" alt="人物" />
        </div>
      </section>

      <section id="works" class="works-section">
        <h2>作品展示</h2>
        <div class="work-item">
          <img src="/src/assets/psc.jpg" alt="作品1" />
        </div>
        <div class="work-item">
          <img src="https://picsum.photos/1200/600?random=2" alt="作品2" />
        </div>
        <div class="work-item">
          <img src="https://picsum.photos/1200/600?random=3" alt="作品3" />
        </div>
      </section>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

.gezi {
  background-color: #ffffff;
  background-image:
    linear-gradient(to right, #ccc 1px, transparent 1px),
    linear-gradient(to bottom, #ccc 1px, transparent 1px);
  background-size: 30px 30px;
  color: #222;
  line-height: 1.6;
  min-height: 100vh;
}

.container {
  max-width: 90%;
  margin: 0 auto;
  padding: 20px 15px;
}

/* 顶部左右布局 */
.top-section {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  background: #fff;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 0 8px rgb(0 0 0 / 0.1);
  align-items: center;
}

/* 左侧介绍区域 */
.left {
  flex: 1 1 320px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.title {
  font-size: 5rem;
  font-weight: 700;
  margin: 0 0 20px 0;
  color: #111;
}

/* 按钮组 */
.btn-group {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.btn-group {
  min-width: 140px;
  font-size: 1rem;
  padding: 12px 20px;
}

button {
  width: 80%;
  font-size: 150%;
}

/* 右侧人物立绘 */
.right {
  flex: 1 1 320px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.right img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
}

/* 作品展示 */
.works-section {
  margin-top: 40px;
}

.works-section h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #222;
}

.work-item {
  margin-bottom: 30px;
}

.work-item img {
  width: 100%;
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgb(0 0 0 / 0.1);
  transition: transform 0.3s ease;
}

.work-item img:hover {
  transform: scale(1.03);
}

/* 响应式 */
@media (max-width: 900px) {
  .top-section {
    flex-direction: column;
    padding: 20px;
  }
  .btn-group {
    justify-content: center;
    gap: 15px;
  }
  .btn-group n-button {
    min-width: 120px;
    font-size: 0.9rem;
  }
}
</style>
