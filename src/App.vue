<template>
  <div id="app">
    <m-header></m-header>
  </div>
</template>
<script  type="text/ecmascript-6">
import MHeader from './components/m-header/m-header'
export default {
  components: {
    MHeader
  }
}
</script>


<style lang="stylus" scoped>
@import "common/stylus/variable"
  
#app
  color: $color-theme-d
</style>
