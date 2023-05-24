<script setup>
import ProfileItem from './ProfileItem.vue'
</script>

<template>
  <ProfileItem>
    <template #heading>Books</template>
    ewrwrwerewr
  </ProfileItem>
  <ProfileItem>
    <template #heading>Genres</template>

  </ProfileItem>
  <ProfileItem>
    <template #heading>Moods</template>

  </ProfileItem>
  <ProfileItem>
    <template #heading>Book Length</template>

  </ProfileItem>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>