<template>
  <div class="homeBox">
    <div class="header">
      <Seek></Seek>
    </div>
    <div class="body">
      <div class="bodyH"></div>
      <div class="bodyB"></div>
    </div>
  </div>
</template>

<script>
import Seek from '../../components/seek'

export default {
  data () {
    return {}
  },

  components: {
    Seek
  },
  methods: {}
}
</script>

<style lang="less" scoped>
.homeBox {
  width: 100%;
  height: 100vh;
  background-color: #ffcc00;
  .header {
    height: 82px;
    margin-bottom: 20px;
  }
  .body {
    width: 95%;
    margin: auto;
    .bodyH {
      width: 90%;
      margin: auto;
      background: #fff;
      height: 50px;
      border-radius: 20px 20px 0 0;
      box-shadow: 0px 9px 10px 0px #999 ;
    }
    .bodyB {
      width: 100%;
      height: 250px;
      background: #fff;
      border-radius: 20px 20px 0 0;
      box-shadow: 0px 9px 10px 0px #999 ;
    }
  }
}
</style>
