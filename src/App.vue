<template>
  <div>
    <router-view></router-view>

    <van-tabbar route>
      <van-tabbar-item icon="home-o" to="/">้ฆ้กต</van-tabbar-item>
      <van-tabbar-item icon="user-o" to="/user">ๆ็</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less" scoped></style>
