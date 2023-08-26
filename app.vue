<script setup lang="ts">
import TopBar from "~/components/index/TopBar.vue";
</script>
<template>
  <div class="common-layout">
    <el-container>
      <el-header>
        <TopBar></TopBar>
      </el-header>
      <el-main style="min-height: 500px">
        <NuxtPage></NuxtPage>
      </el-main>
      <el-footer style="display: flex;justify-content: center">
        <el-text type="info">
          网站建设者：曾子愚
          邮箱：Zengtudor@outlook.com
          技术栈：Vue3 Vite Nuxt3 ...
          (本人初中生有意向可以与我讨论)
        </el-text>
      </el-footer>
    </el-container>
  </div>
</template>
<style scoped>

</style>