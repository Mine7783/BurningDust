<template>
  <div class="searchbarContainer">
    <div class="searchArea">
      <div class="serachEngine">
        <ul>
          <li>网页</li>
          <li>百度</li>
          <li>谷歌</li>
          <li>必应</li>
          <li>图片</li>
          <li>种子</li>
          <li>学术</li>
        </ul>
      </div>
      <div class="searchForm">
        <input type="text" placeholder="百度一下你就知道">
        <button>搜索</button>
      </div>
    </div>
    
  </div>
</template>
<script>
export default {
  name: 'Searchbar'
}
</script>
<style lang="less" rel="stylesheet/less" scoped>
  .searchbarContainer{
    width: 1200px;
    height: 150px;
    background-color: #ffffff;
    margin: 0 auto;
    border-top: 1px solid rgb(231, 231, 231);
    padding: 40px 0 70px;
      .searchArea{
        width: 650px;
        height: 100px;
        margin: 0 auto;
         .serachEngine{
           ul{
             width: 470px;
             height: 33px;
             display: flex;
             justify-content: space-between;
              li{
                height: 33px;
              }
           }
         }
      }
  }
</style>