<script setup lang="ts">

</script>

<template>
  <div class="header">
    <!--学校首页-搜索-?用户-->
    <div class="top-nav">
      <div class="container">
        <a href="/" class="home">学校主页</a>
        <div>
          <form class="search">
            <input type="text" name="q">
            <button type="submit">S</button>
          </form>
          <div class="user" v-if="true">你好，……</div>
        </div>
      </div>
    </div>

    <!--Logo-学校名-标签-->
    <div class="quick-nav">
      <div class="container">
        <div class="info">
          <img src="/vite.svg" class="logo" alt="学校图标"/>
          <div class="names">
            <span>学校中文</span>
            <span>学校英文</span>
          </div>
        </div>
        <div class="tabs">
          <div class="tab">网站首页</div>
          <div class="tab">新闻动态</div>
          <div class="tab">产学研成果展示</div>
          <div class="tab">师生预约窗口</div>
          <div class="tab">借用日历查询</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>