<template>
  <div id="app">
    <p>
      <router-link to="/icon">icon</router-link>
      <router-link to="/button">button</router-link>
      <router-link to="/radio">radio</router-link>
      <router-link to="/checkbox">checkbox</router-link>
      <router-link to="/select">select</router-link>
      <router-link to="/input">input</router-link>
      <!-- <router-link to="/scrollbar">scrollbar</router-link> -->
      <router-link to="/notification">notification</router-link>
      <router-link to="/message">message</router-link>
      <router-link to="/dialog">dialog</router-link>
    </p>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
#app {
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  display: inline-block;
  margin: 5px;
  color: #20a0ff;
}

.router-link-active {
  color: #fff;
  background: #20a0ff;
}
</style>
