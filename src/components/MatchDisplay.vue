<script lang="ts" setup>
defineProps<{
  tournament: string
  date: string
  player1: string
  player2: string
  score1: string
  score2: string
}>()
</script>

<template>
  <div class="w-9/10 bg-secondary p-4">
    <div class="flex justify-between text-xs mb-2">
      <div>{{ tournament }}</div>
      <div>{{ date }}</div>
    </div>
    <div class="flex justify-center text-lg -mb-2">
      <div>{{ score1 }} - {{ score2 }}</div>
    </div>
    <div class="flex justify-between text-lg">
      <div>{{ player1 }}</div>
      <div>{{ player2 }}</div>
    </div>
  </div>
</template>
