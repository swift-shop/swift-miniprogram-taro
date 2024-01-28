<template>
  <view class="index">
    <text>{{ msg }}</text>
  </view>
  <nut-button></nut-button>
  <nut-cell title="展示弹出层" is-link @click="show = true"></nut-cell>
  <nut-popup :style="{ padding: '30px 50px' }" v-model:visible="show">正文</nut-popup>
</template>

<script setup lang="ts">
import {ref} from 'vue'

const msg = ref('Hello, world! nut')
const show = ref(false);
</script>