<script setup lang="ts">
</script>

<template>
    <div
        v-if="$slidev.nav.currentPage === 2"
        v-motion
        :initial="{ x: -450 }"
        :enter="{ x: 0,  transition: { duration: 1500 } }">
        <span class="user-title">竟有这么棒的人</span>
    </div>
</template>
<style lang="less" scoped>
    .user-title {
        background: linear-gradient(102.7deg, rgb(253, 218, 255) 8.2%, rgb(223, 173, 252) 19.6%, rgb(173, 205, 252) 36.8%, rgb(173, 252, 244) 73.2%, rgb(202, 248, 208) 90.9%);
        -webkit-background-clip: text;
        -moz-background-clip: text;
        -webkit-text-fill-color: transparent;
        -moz-text-fill-color: transparent;
    }
</style>