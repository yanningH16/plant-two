<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
@import './assets/stylus/variable'
#app
  width 100%
  height 100%
  position fixed
  display flex
</style>
