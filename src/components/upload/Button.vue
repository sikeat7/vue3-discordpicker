<script>
import { defineComponent } from 'vue'

export default defineComponent({
  emits: ['click']
})
</script>

<template>
  <img src="./../../assets/upload.svg" alt="Gif button" width="10" height="10" class="ml-5 w-5 transition duration-200 filter hover:brightness-150 cursor-pointer transform hover:scale-110" @click="$emit('click')">
</template>