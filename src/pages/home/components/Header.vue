<template>
  <header class="header">
    <span>
      <i class="iconfont product-icon">&#xe66c;</i>产品
    </span>
    <span class="iconfont person-icon">&#xe676;</span>
  </header>
</template>

<script>
export default {
  name: 'HomeHeader',
  data () {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.header {
    height: 88px;
    line-height: 88px;
    overflow: hidden;
    display: flex;
    justify-content: space-between;
    color: $fontColor;
    font-size: 32px;
    font-family: '黑体';
    .product-icon {
        margin-right: 10px;
    }
    .person-icon {
        font-size: 40px;
    }
}
</style>
