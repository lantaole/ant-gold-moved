<template>
  <div class=" bgfff top ">
    <div class="container">
      <div class="ht60 lht60">
        <router-link to="/" class="inline-block left">
          <img src="/static/img/logo.png" alt="" class="vtc-mid inline-block">
        </router-link>
        <div class="top-list">
          <router-link to="">
            首页
          </router-link>
          <router-link to="">
            产品列表
          </router-link>
          <router-link to="">
            合规咨询
          </router-link>
          <router-link to="">
            关于我们
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default{
    data(){
      return {
        sContent:"This is hello components"
      }
    }
  }
</script>

<style lang="scss">
  @import 'src/css/common';
  .top{
    box-shadow: 0 2px 3px 0 rgba(241,241,241,0.5)
  }
  .top-list{
    float: left;
    a{
      display: inline-block;
      color: #333;
      font-size: 16px;
      width: 100px;
      text-decoration: none;
      text-align: center;
    }
  }
</style>
