<template>
  <div>
    <div>
      <h1>登录</h1>
    </div>
    <div>
      <input placeholder="请输入用户名"/>
    </div>
    <div>
      <input placeholder="请输入密码"/>
    </div>
    <div>
      <button @click="toLogin">登录</button>
    </div>
  </div>
</template>

<script>
const {
  ipcRenderer,
  remote
} = require('electron');

export default {
  methods: {
    toLogin() {
      this.$router.push({path: '/home1.html'})
    }
  }
}
</script>

<style>

</style>