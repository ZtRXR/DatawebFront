<script setup lang="ts">

import { ref } from 'vue'

// const handleSelect = (key: string, keyPath: string[]) => {
//   console.log(key, keyPath)
// }
</script>

<template>
  <el-menu
      :default-active="'/'"
      class="el-menu-demo"
      mode="horizontal"
      :router="true"
  >
    <el-menu-item index="/">ZZIYU DataWeb</el-menu-item>
    <div class="flex-grow" />
    <el-sub-menu index="data/all">
      <template #title>数据收集</template>
      <el-menu-item index="data/all">总览</el-menu-item>
      <el-menu-item index="data/bilibili">bilibili</el-menu-item>
      <el-menu-item index="data/baidu">baidu</el-menu-item>
      </el-sub-menu>
    <el-sub-menu index="tools">
      <template #title>工具</template>
      <el-menu-item index="tools/qqazk/index">笔顺码字典</el-menu-item>
    </el-sub-menu>
  </el-menu>
</template>

<style scoped>

</style>