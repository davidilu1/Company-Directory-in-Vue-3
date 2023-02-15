<script setup>
  import MainCards from './MainCards.vue'
  import MainPagination from './MainPagination.vue'
  import MainSearch from './MainSearch.vue'
</script>

<template>
  <div class="wrapper">
    <MainSearch />
    <MainCards />
    <MainPagination />
  </div>
</template>

<style scoped lang="postcss">
.wrapper {
  @apply container mx-auto flex flex-col gap-4 py-4;
}
</style>
