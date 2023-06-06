<template>
    <div class="bg flex items-center justify-center h-[700px]" :style="`background-image: linear-gradient(to top, rgba(0, 0, 0, 1), rgba(0, 0, 0, 0)), url(/${banner})`">
        <div class="cont flex flex-col max-w-[1280px] m-auto w-full h-[90%] justify-between text-whito"> 
            <div class="top w-full flex justify-between ">
                <div class="left w-24"><img :src="`/${logo}`" alt="" class="w-full"></div>
                <div class="right h5">Realizado por Yingying Cheng, Marco García y Laura Rodriguez</div>
            </div>
            <div class="text flex justify-between w-full items-center">
                <div class="nombres flex flex-col">
                    <div class="h1">Manual de Marca</div>
                    <div class="h3"> {{ title }}</div>
                </div>

                <slot />
            </div>

        </div>
    </div>
</template>


<script setup>
defineProps({
    title: String,
    logo: String,
    banner: String,
})
</script>


<style lang="sass" scoped>
    .bg
        background-repeat: no-repeat
        background-size: cover
</style>