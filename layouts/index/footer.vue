<template>
  <div class="bottom-0 bg-violet-900 w-auto justify-center flex ">
    <audio :src="music" controls/>
  </div>
</template>

<script setup lang="ts">
import { useSound } from '@vueuse/sound'
import music from 'assets/sound/Anh-Mo-Anh-Khang.mp3'

const { play } = useSound(music)
</script>