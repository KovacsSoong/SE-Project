<template>
  <div id="app">
    <router-view/>
    <!-- router-link to=/ 表示就显示在当前页面上 -->
    <!--
    <router-link to="/" class="router-link">主页</router-link>
    <router-link to="/SearchPage" class="router-link">课程查询页面</router-link>
    <router-link to="/ProjectPage" class="router-link">培养方案页面</router-link>
    <router-link to="/SetDatePage" class="router-link">设置选课时间</router-link>
    <router-link to="/StudentListPage" class="router-link">学生列表</router-link>
    <router-link to="/QueryStudentPage" class="router-link">查找学生</router-link>
    -->
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.router-link {
  float: left;
  font-weight: normal;
  font-family:"Microsoft YaHei", "Microsoft JhengHei Light", Helvetica, sans-serif;
  cursor: pointer;
  background: #abbac3;
  color: #ffffff;
  font-size: 16px;
  padding: 10px 20px 10px 20px;
  border: solid #abbac3 1px;
  text-decoration: none;
  margin: 5px 2px 10px 2px;
}
.router-link:hover {
  color: #ffffff;
  background: #888888;
  border: solid #888888 1px;
  text-decoration: none;
}
</style>
