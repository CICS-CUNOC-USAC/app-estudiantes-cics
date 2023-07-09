<template>
  <NuxtLayout />
</template>
<script setup lang="ts">
useHead({
  titleTemplate: title => (title ? `${title} | CUNOC App` : 'CUNOC - Aplicación para estudiantes')
})
</script>
