<template>
  <view class="index">
   loading页面
  </view>
</template>

<script>
import { ref} from 'vue'

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

