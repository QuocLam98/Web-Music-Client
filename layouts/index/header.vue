<template>
  <div class="input-group w-auto justify-center bg-violet-900 h-auto">
    <div class="join my-1">
      <input class="input input-bordered join-item focus:outline-none border-0 bg-violet-500 input-sm w-full" placeholder="Tìm kiếm bài hát, tên ca sĩ...." :value="name"/>
      <button class="btn join-item bg-violet-500 hover:bg-violet-500 rounded-r-full border-0 btn-sm">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" /></svg>
      </button>
    </div>
  </div>
</template>

<script setup lang="ts">
const name = ref('')
</script>