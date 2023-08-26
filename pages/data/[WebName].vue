<script setup lang="ts">
import {useRoute} from "vue-router";
const route = useRoute()
let webName = route.params.WebName
</script>

<template>
这是 {{webName}} 数据展示
</template>

<style scoped>

</style>