<script setup lang="ts">
    import AudioPlayer from 'vue3-audio-player'
    import 'vue3-audio-player/dist/style.css'

    import { ref } from 'vue'

</script>
<template>
    <AudioPlayer
        ref="audioPlayerRef"
        :option="{
            src: '/media/main.ogg',
            title: '稳稳的幸福',
            coverImage: '/images/20231009135752.jpg',
            progressBarColor: '#90dcc1',
            indicatorColor: '#f8acac',
            autoPlay: false
        }"
    />
  </template>