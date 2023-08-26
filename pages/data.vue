<script setup lang="ts">
import {useRoute,useRouter} from "vue-router";
const route = useRoute()
const router = useRouter()
//检查访问的数据库是否为空，重定向
if (route.params.WebName==undefined){
  router.push("/data/all")
}
</script>

<template>
  Data father {{}}
  <NuxtPage></NuxtPage>
</template>

<style scoped>

</style>