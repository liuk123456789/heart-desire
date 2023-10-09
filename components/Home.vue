<script setup lang="ts">
    import CustomAudio from './CustomAudio.vue'
</script>

<template>
    <h2 class="mt-60 main-title">烟火向星辰，所许皆成真</h2>
    <CustomAudio class="absolute custom-audio" />
    <div class="pt-12">
    <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer link-title" hover="bg-white bg-opacity-10">
        旅者，探索吧<circum:face-smile color="rgb(254, 211, 252)" /><fxemoji:right class="ml-2" />
    </span>
    </div>
</template>

<style lang="less" scoped>
    .main-title {
        background-image: linear-gradient(111.4deg, #EE7171 1%, #F6D794 58%);
        background-size: 100%;
        -webkit-background-clip: text;
        -moz-background-clip: text;
        -webkit-text-fill-color: transparent;
        -moz-text-fill-color: transparent;
    }

    .custom-audio {
        top: 3rem;
        left: 50%;
        transform: translateX(-50%);
        :deep(.audio__player-title) {
            background-image: linear-gradient(107.7deg, #65a88f -31.7%, #90dcc1 18.2%, #e1cb96 36.3%, #fba696 89.6%, #fa3641 100.5%);
            -webkit-background-clip: text;
            -moz-background-clip: text;
            -webkit-text-fill-color: transparent;
            -moz-text-fill-color: transparent;
        }
        :deep(.audio__player-time) {
            background: radial-gradient(169px at -2.9% 12.9%, rgb(247, 234, 163) 0%, rgba(236, 180, 238, 0.56) 46.4%, rgb(163, 203, 247) 100.7%);
            -webkit-background-clip: text;
            -moz-background-clip: text;
            -webkit-text-fill-color: transparent;
            -moz-text-fill-color: transparent;
        }

        :deep(.audio__player-play-icon) {
            padding: 0.3rem;
            opacity: 0.8;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            background-image: linear-gradient(111.4deg, rgb(209, 231, 235) 7.4%, rgb(238, 219, 199) 51.4%, rgb(255, 159, 122) 82.6%, rgb(255, 109, 58) 100.2%);
            img {
                width: 1.2rem;
                height: 1.2rem;
            }
        }
    }

    .link-title {
        background-image: radial-gradient(circle at 10% 20%, rgb(222, 168, 248) 0%, rgb(168, 222, 248) 21.8%, rgb(189, 250, 205) 35.6%, rgb(243, 250, 189) 52.9%, rgb(250, 227, 189) 66.8%, rgb(248, 172, 172) 90%, rgb(254, 211, 252) 99.7%);
        background-size: 100%;
        -webkit-background-clip: text;
        -moz-background-clip: text;
        -webkit-text-fill-color: transparent;
        -moz-text-fill-color: transparent;
    }
</style>