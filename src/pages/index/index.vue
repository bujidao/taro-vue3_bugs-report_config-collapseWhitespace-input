<template>
  <view class="index">
    <text>{{ msg }}</text>
    <input type="text" style="background: #aaa;" placeholder="请输入关键字">
  </view>
</template>

<script>
import { ref } from 'vue'
import './index.scss'

export default {
  name: 'homePage',
  setup () {
    const msg = ref('Hello world')
    return {
      msg
    }
  }
}
</script>
