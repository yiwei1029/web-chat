<template>
  <div>id: {{ uid }}, name: {{ name }}</div>
</template>
<script setup lang="ts">
defineProps<{
  uid: string
  name: string
}>()
</script>
