<template>
    <div>看啥看自己走</div>
</template>

<script setup>
import { useRoute } from 'vue-router';
console.log('我是navlocate组件的路由地址', $route)
// 使用 $router.replace() 替换当前路由
this.$router.replace('/new-route');
</script>

<style lang="scss" scoped></style>
