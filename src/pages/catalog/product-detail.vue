<script>
import {ref} from 'vue'

export default {
  setup() {
    const msg = ref('pdp')
    return {
      msg
    }
  }
}
</script>

<template>
  <view class="index">
    <text>{{ msg }}</text>
  </view>
</template>

<style scoped>

</style>