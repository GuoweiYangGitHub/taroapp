<template>
  <view class="index">
    <view>下面tabbar</view>
  </view>
</template>

<script>
import { ref} from 'vue'
import './index.less'

export default {
  // onLoad
  onLoad () {},

  // onReady
  onReady () {},

  // 对应 onShow
  onShow () {},

  // 对应 onHide
  onHide () {},

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

