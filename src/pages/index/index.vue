<template>
  <view>
    <!-- 搜索框 -->
    <view class="search">
      <!-- 输入框 -->
      <view class="input-box">
        <input type="text" />
      </view>
      <!-- 搜索结果 -->
    </view>
    <!-- 轮播图 -->
    <swiper
      class="slide"
      autoplay
      circular
      indicator-dots
      indicator-color="rgba(255, 255, 255, .3)"
      indicator-active-color="#fff"
    >
      <swiper-item>
        <navigator>
          <image src="../../static/uploads/banner1.png"></image>
        </navigator>
      </swiper-item>
      <swiper-item>
        <navigator>
          <image src="../../static/uploads/banner2.png"></image>
        </navigator>
      </swiper-item>
      <swiper-item>
        <navigator>
          <image src="../../static/uploads/banner3.png"></image>
        </navigator>
      </swiper-item>
    </swiper>
    <!-- 主导航 -->
    <view class="navs">
      <navigator>
        <image src="../../static/uploads/icon_index_nav_4@2x.png"></image>
        <image src="../../static/uploads/icon_index_nav_3@2x.png"></image>
        <image src="../../static/uploads/icon_index_nav_2@2x.png"></image>
        <image src="../../static/uploads/icon_index_nav_1@2x.png"></image>
      </navigator>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {};
  },
  onLoad() {},
  methods: {}
};
</script>

<style lang="less">
.search {
  .input-box {
    background-color: #ea4451;
    padding: 20rpx;

    input {
      background-color: #ffffff;
      border-radius: 8rpx;
      height: 60rpx;
    }
  }
}
swiper {
  width: 750rpx;
  height: 340rpx;
  image {
    width: 750rpx;
    height: 340rpx;
  }
}

.navs {
  height: 193rpx;
  display: flex;
  justify-content: space-around;

  image {
    width: 128rpx;
    height: 140rpx;
  }
}
</style>
