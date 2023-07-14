<script setup>
import { ref } from "vue";

import assetsImg from "dt-assets";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1><el-button type="primary">Hello Daotin</el-button></h1>

  <el-image :src="assetsImg.unicom"></el-image>

  <hr />
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
