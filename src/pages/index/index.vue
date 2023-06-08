<template>
  <view class="content">
    <input class="input" confirm-type="search" placeholder="键盘右下角按钮显示为搜索">
    <view class="iconfont icon-saoma"></view>
  </view>
</template>

<script setup>

</script>

<style lang="less">
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  .input {
    width: 90%;
    height: 35px;
    border: 1px solid #999;
  }
}
</style>
