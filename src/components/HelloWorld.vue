<template>
  <div id="building">
    <h1>HelloWorld</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
#building {
  // 设置背景图片
  background: url("https://s2.loli.net/2022/05/25/eqgS3JWUHd8E7Yf.png");
  width: 100%;
  height: 100%;
  // 设置背景图片的位置为固定
  position: fixed;
  // 根据原始比例进行裁切
  background-size: cover;
}
</style>
