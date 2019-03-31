<template>
  <div id="home">
    <home-header></home-header>
  </div>
</template>

<script>
import HomeHeader from '@/pages/home/components/Header'
export default {
  name: 'Home',
  components: {
    HomeHeader
  }
}
</script>

<style lang="scss" scoped>
#home {
    min-height: 100vh;
    background: $bgLineGradient;
    padding: 0 30px;
}
</style>
