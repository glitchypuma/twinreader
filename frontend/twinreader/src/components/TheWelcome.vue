<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>How It Works</template>
    We take your favorite book titles, genres, and authors to pair you with readers that have the best taste- your taste!
    You can also include your preferred book moods, length, and media-type for better results.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support</template>
      ?????
  </WelcomeItem>
</template>
