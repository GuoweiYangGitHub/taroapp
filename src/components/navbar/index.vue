<template>
  <view class="index">
     <van-nav-bar
      title="标题"
      left-text="返回"
      left-arrow
      @click-left="onClickLeft"
    />
  </view>
</template>

<script>
import { NavBar } from 'vant';

import { ref } from 'vue'
import './index.less'

export default {
  // components: {
  //   NavBar
  // },
  // onLoad
  onLoad () {},

  // onReady
  onReady () {},

  // 对应 onShow
  onShow () {},

  // 对应 onHide
  onHide () {},

  onClickLeft(){

  },
  // 对应 onPullDownRefresh
  onPullDownRefresh () {},

  setup () {
    const msg = ref('Hello world')

    return {
      msg
    }
  }
}
</script>
