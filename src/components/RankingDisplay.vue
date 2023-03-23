<script setup lang="ts">
defineProps<{
  ranking: string
  placement: string
  players: string
}>()
</script>

<template>
  <div class="w-9/10 h-fit p-4 bg-secondary flex justify-between">
    <h1>{{ ranking }}</h1>
    <div>{{ placement }}/{{ players }}</div>
  </div>
</template>

