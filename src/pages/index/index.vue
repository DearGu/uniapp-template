<template>
  <view class="content">
    <image class="logo" src="/static/logo.png" />
    <view class="text-area">
      <text class="title">{{ title }}123</text>
    </view>
    <uni-badge text="1" />
  </view>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const title = ref('Hello');
</script>

<style lang="scss">
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  .logo {
    height: 200rpx;
    width: 200rpx;
    margin: 200rpx auto 50rpx;
  }

  .text-area {
    display: flex;
    justify-content: center;
  }

  .title {
    font-size: 36rpx;
    color: #8f8f94;
  }
}
</style>
