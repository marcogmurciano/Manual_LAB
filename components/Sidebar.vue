<template>
    <div class="bg">
        <SideItem v-for="(item, i) in array" :item="item" :index="i" :array="subArray[i]"> {{ item }} </SideItem>
    </div>
</template>


<script setup>
defineProps ({
    array: Array,
    subArray: Array,
})
</script>


<style lang="sass" scoped>

</style>