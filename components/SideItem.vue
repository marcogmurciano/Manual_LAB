<template>
  <div class="bg">
    <div class="h4 flex gap-2 items-center" @click="open()">
      <slot />
      <ph-caret-down :size="16" :weight="bold" :class="volt" class="volti" />
    </div>
    <div class="dropdown flex flex-col px-1">
      <div
        class="cuerpo"
        v-for="(el, i) in props.array"
        v-if="opened"
        @click="scrollTo(el, i)"
      >
        {{ el }}
      </div>
    </div>
  </div>
</template>

<script setup>
import { PhCaretDown } from "@phosphor-icons/vue";


const props = defineProps({
  index: Number,
  array: Array,
  item: String,
});

const itemAsSlug = computed(() => {
  return props.item.split(" ")[0];
});

const scrollTo = (el, i) => {
  console.log(el, i);
  let articles = [];
  if (document) {
    console.log(`.${itemAsSlug.value} .article_scrolable`);
    articles = document.querySelectorAll(
      `.${itemAsSlug.value} .article_scrollable`
    );
    if (articles[i]) articles[i].scrollIntoView({ behavior: "smooth" });
  }
};

const opened = ref(false);
const volt = ref("");

const open = () => {
  opened.value = !opened.value;
  if (opened.value) {
    volt.value = "voltereta";
  } else {
    volt.value = "";
  }
};
</script>

<style lang="sass" scoped>
.h4
    @apply border-y border-whito bg-gray2 py-2 px-3
.cuerpo
    @apply border-y border-gray2 bg-gray1 py-2 px-3

.voltereta
    transform: rotate(180deg)
    transition: transform 0.3s ease-out
.volti
    transition: transform 0.3s ease-out
</style>
