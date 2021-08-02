<template>
  <div id="home">
    <h2>首页</h2>
    <nav-bar><div slot="center">购物街</div></nav-bar>
  </div>
</template>

<script>
import NavBar from "../../components/common/navbar/NavBar";

export default {
  name: "Home",
  components: {
    NavBar
  }
}
</script>

<style scoped>
#home{
  height: 44px;
}
</style>

