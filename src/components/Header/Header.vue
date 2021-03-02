<template>
  <div class="headerContainer" >
    <div class="logo">W.</div>
    <div class="menu"></div>
  </div>
</template>
<script>
export default {
  name: 'Header'
}
</script>
<style lang="less" rel="stylesheet/less" scoped>
  .headerContainer{
    width: 1200px;
    height: 150px;
    background-color: #ffffff;
    margin: 0 auto;
      .logo{
        height: 150px;
        line-height: 150px;
        width: 200px;
        text-align: center;
        font-weight:bolder;
        font-size: 24px;
      }
  }
</style>