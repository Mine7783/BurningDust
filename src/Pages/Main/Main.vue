<template>
  <div class="mainContainer" >
    <Header/>
    <Searchbar/>
  </div>
</template>
<script>
// 引入组件
import Header from '../../components/Header/Header'
import Searchbar from '../../components/Searchbar/Searchbar'
export default {
  name: 'Main',
  components:{
    Header,
    Searchbar
  }
}
</script>
<style lang="less" rel="stylesheet/less" scoped>
  .mainContainer{
    width: 100%;
    padding-top: 50px;
    background-color: #ededed;
  }
</style>