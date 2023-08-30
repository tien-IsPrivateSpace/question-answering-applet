<script setup></script>

<template>
  <div>
    <header class="flex header items-center">
      <img src="@/static/logo.png" />
      <div class="flex-col header-spans">
        <span>超大佬</span>
        <span>超大佬的小程序</span>
      </div>
    </header>
    <main>
      <h3 v-for="item in 5">列表{{ item }}</h3>
    </main>
  </div>
</template>

<style lang="scss" scoped>
.header {
  padding: 20rpx;
  background: -webkit-linear-gradient(315deg, #42d392 25%, #647eff);

  img {
    width: 100rpx;
    height: 100rpx;
    border-radius: 50%;
  }
  .header-spans {
    margin-left: 10rpx;

    span:nth-child(1) {
      font-size: 30rpx;
    }
    span:nth-child(2) {
      font-size: 24rpx;
      color: #666;
    }
  }
}
</style>
