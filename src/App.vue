<template>
  <div id="app">
    <el-container>
      <el-header height="100px"></el-header>
      <el-main></el-main>
      <el-footer height="350px"></el-footer>
    </el-container>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" rel="stylesheet/scss">
  @import "statics/css/index.scss";
  .el-header {
    background-color: #040404;
    color: #333;
    line-height: 100px;
  }
  .el-main {
    background-color: #ededed;
    min-height: calc(100vh - 454px);
    color: #333;
    text-align: center;
  }

  .el-footer {
    margin-top: 60px;
    background-color: #fafafa;
    color: #333;
    text-align: center;
    line-height: 60px;
  }

</style>

