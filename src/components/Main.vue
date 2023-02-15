<script setup>
import MainCards from '/Users/davidilunga/Desktop/projects/Company-Directory-in-Vue-3/src/components/Maincards.vue'
import MainPagination from '/Users/davidilunga/Desktop/projects/Company-Directory-in-Vue-3/src/components/MainPagination.vue'
import MainSearch from '/Users/davidilunga/Desktop/projects/Company-Directory-in-Vue-3/src/components/MainSearch.vue'
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
