<template>
  <div class="seekBox">
    <div class="seekTop">
      <img src="../../static/images/b.png" alt class="bBox" />
      <input type="text" class="seekInp" placeholder="想吃啥包子？" />
    </div>
  </div>
</template>

<style lang="less" scoped>
.seekBox {
  width: 70%;
  height: 100%;
  .seekTop {
    height: 100%;
    display: flex;
    align-items: flex-end;
    justify-content: flex-end;
    width: 100%;
    .bBox {
      width: 30px;
      height: 30px;
      vertical-align: middle;
      margin-right: 2px;
    }
    .seekInp {
      width: 75%;
      height: 30px;
      border-radius: 15px;
      background: #fff;
      padding-left: 15px;
      font-size: 13px;
    }
  }
}
</style>