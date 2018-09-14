<template>
  <div id="chain">
    <div class="page-title">
      <img class="logo" src="../assets/logo.png" alt="">
    </div>
    <div class="page-content"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" rel="stylesheet/less" scoped>
#chain{
  background: #000;
  height: 100%;
  .page-title{
    text-align: left;
    .logo{
      margin-left: 64px;
      width: 200px;
      height: 60px;
    }
  }
}
</style>
