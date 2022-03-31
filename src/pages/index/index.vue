<template>
  <view class="index">
    <navbar />
    <text>{{ msg }}</text>
    <tabbar />
  </view>
</template>

<script>
import { ref } from 'vue'
import tabbar from '@/components/tabbar/index.vue';
import navbar from '@/components/navbar/index.vue';
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
  },

  components:{
    tabbar,
    navbar
  }
}
</script>
