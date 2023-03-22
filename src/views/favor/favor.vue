<template>
  <div class="favor" ref="favorRef">
    <h2>请先登录，但是没有登录功能</h2>
  </div>
</template>

<script setup>
import { ref } from "vue";
import useScroll from "@/hooks/useScroll";

const favorRef = ref();

useScroll(favorRef);
</script>

<style lang="less" scoped>
.favor {
  text-align: center;
}
</style>
