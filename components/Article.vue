<template>
    <div class="bg flex gap-8 pb-12 w-full">
        <div class="cont flex flex-col gap-2 w-full">
            <video :src="`/${el}`" controls class="w-full" v-for="el in props.video"  v-if="videoBool"/>
            <img :src="`/${el}`" alt="" class="w-full" v-for="el in props.img" v-else>
        </div>
        <div class="text w-[50%] flex flex-col gap-8">
            <div class="h2"> {{ props.tit }} </div>
            <div class="cuerpo">
                <slot />
            </div>
    </div>
</div>
</template>


<script setup>
    const props = defineProps({
        tit: String,
        img: Array,
        video: Array,
    })
    let videoBool = false
    if (props.img.length === 0) {
        videoBool = true
    } else {
        
    }
</script>


<style lang="sass" scoped>

</style>


