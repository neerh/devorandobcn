<template>
  <div class="p-6">
    <p class="text-4xl font-semibold text-primary">Restaurantes:</p>
    <RestaurantTable />
    <p class="text-4xl font-semibold text-primary">Bliblablublu:</p>
    <PostContainer />
  </div>
</template>

<script setup>
import PostContainer from './components/PostContainer.vue';
import RestaurantTable from './components/RestaurantTable.vue';
</script>

<style>
  body{
    @apply bg-white;
  }
</style>
