<template>
<div class="feature">
  <a href="https://act.mogujie.com/zzlx67" class="feature-item">
    <img src="~assets/img/home/recommend_bg.jpg" alt="">
  </a>
</div>
</template>

<script>
  export default {
    /**
     * 特性组件
     */
    name: "FeatureView"
  }
</script>

<style scoped>
.feature{
  width: 100%;
}
.feature-item {
  flex: 1;
  text-align: center;
}

.feature img {
  width: 100%;
  height: 80%;
  margin-bottom: 10px;
}
</style>
