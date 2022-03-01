<!--
 * @Description: 关于我们页面组件，未完成
 * @Author: hai-27
 * @Date: 2020-02-07 16:23:00
 * @LastEditors: hai-27
 * @LastEditTime: 2020-03-12 19:36:46
 -->
<template>
  <div class="about" id="about" name="about">
    <div class="about-header">
      <div class="about-title">
        <i class="el-icon-tickets" style="color: #ff6700;"></i>
        关于我们
      </div>
    </div>
    <div class="about-content">
        本项目采用vue全家桶(vue+vue-router+vuex+axios)技术,可以帮助大家更好的掌握vue全家桶技术去开发项目，服务端已部署在云服务器上，各项功能与接口设计一致
    </div>
  </div>
</template>
<script>

export default {
  
};
</script>
<style scoped>
.about {
  background-color: #f5f5f5;
}
.about .about-header {
  height: 64px;
  background-color: #fff;
  border-bottom: 2px solid #ff6700;
}
.about .about-header .about-title {
  width: 1225px;
  margin: 0 auto;
  height: 64px;
  line-height: 64px;
  font-size: 28px;
}
.about .content {
  padding: 20px 0;
  width: 1225px;
  margin: 0 auto;
}
.about .content .goods-list {
  margin-left: -13.7px;
  overflow: hidden;
}
.about .about-content {
  width: 1225px;
  margin: 0 auto;
  background-color: #fff;
}
</style>
