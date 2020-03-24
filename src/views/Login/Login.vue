<template>
  <div id="login">
      这里是登录页面
      <el-row>
  <el-button round>圆角按钮</el-button>
  <el-button type="primary" round>主要按钮</el-button>
  <el-button type="success" round>成功按钮</el-button>
  <el-button type="info" round>信息按钮</el-button>
  <el-button type="warning" round>警告按钮</el-button>
  <el-button type="danger" round>危险按钮</el-button>
</el-row>
  </div>
</template>

<script>
export default {
  name: 'login'
}
</script>
<style lang="scss" scoped>
  #login {
    height: 100vh;
    background-color: #344a5f;
  }
</style>
