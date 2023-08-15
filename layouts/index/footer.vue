<template>
  <div class="bottom-0 bg-violet-900 w-auto justify-center flex ">
    <button class="btn btn-primary btn-sm" @click="() => play">play</button>
  </div>
</template>

<script setup lang="ts">
import { useSound } from '@vueuse/sound'
import music from 'assets/sound/Anh-Mo-Anh-Khang.mp3'

const { play } = useSound(music)
</script>