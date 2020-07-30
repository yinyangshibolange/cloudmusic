<template>
  <div class="header flex justify-between align-center">
    <div class="left flex align-center">
      <h1 class="logo">
        <a hidefocus="true" style="color: #fff; font-weight: 600; ">网易云音乐</a>
      </h1>
      <div class="back-forward">
        <a><i class="iconfont icon-houtui"></i></a>
        <a><i class="iconfont icon-qianjin"></i></a>
      </div>
      <div class="search"></div>
    </div>

    <div class="right flex align-center">
      <div
        class="flex justify-start align-center"
      >
        <div class=" avatar">
          <img src="@/assets/avatar.jpeg" />
        </div>
        <div class=" nickname">mr·hong<i class="iconfont icon-triangledownfill" style="margin-left: 5px;"></i></div>
        <div class=" vip">开通VIP</div>
        <div class=" pifu">
          <i class="iconfont icon-pifu"></i>
        </div>
        <div class=" message">
          <i class="iconfont icon-message"></i>
        </div>
        <div class=" setting">
          <i class="iconfont icon-setting"></i>
        </div>
      </div>
      <div class="flex divier" style="width: 0.1px; height: 18px; border-color: #999; margin: 0 10px;"></div>
      <div class="right-right flex justify-start align-center">
        <div class=" simple">
          <i class="iconfont icon-bianji"></i>
        </div>
        <div class=" minium">
          <i class="iconfont icon-baseline-remove-px"></i>
        </div>
        <div class=" max">
          <i class="iconfont icon-baseline-check_box_outline_blank-px"></i>
        </div>
        <div class=" close">
          <i class="iconfont icon-baseline-close-px"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header {
  padding: 6px 16px;
  background: red;
  .left {
    .logo {
      float: left;
      & > a {
        font-size: 16px;
      }
    }
  }

  .right {
    color: #f2f2f2;
    font-weight: 500;
    font-size: 14px;
    & > div > div {
      padding: 5px 8px;
    }
    .right-right > div {
      padding: 5px 4px;
    }
    i {
    font-size: 16px;
    }
    .nickname i {
      font-size: 10px;
    }
    .avatar {
      & > img {
        width: 28px;
        height: 28px;
        overflow: hidden;
        border-radius: 16px;
      }
    }
  }
}
</style>