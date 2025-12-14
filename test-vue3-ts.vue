<template>
  <div>
    <view @click="submit">提交</view>
    <view @change="change">提交</view>

    <view @change="changeeeeee333">提交</view>
    <view @change="changeeeeee">提交</view>
    <view @change="changeeeeee(item)">提交</view>
    <view>
      <!-- {{ statsBuffer.status }} -->
      {{ statsBuffer.ddddddddddddddddddd }}
      {{ ttt.ddddddddddddddddddd }}
      {{ uuuu.ddddddddddddddddddd }}
    </view>
    <div @click="sss">{{ yyy }}</div>
  </div>
</template>

<script setup lang="ts">
  const statsBuffer = ref({ ddddddddddddddddddd: "" });
  const ttt = ref({ ddddddddddddddddddd: "" });
  const uuuu = ref({ ddddddddddddddddddd: "" });
  const yyy = ref('')
  const changeeeeee = (item) => {
    // TODO: 实现方法逻辑
  };
  const changeeeeee333 = () => {
    // TODO: 实现方法逻辑
  };
  const sss = () => {
    // TODO: 实现方法逻辑
  }

</script>

<style lang="scss" scoped></style>
