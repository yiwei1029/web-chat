<template>
  <div>
    Login
    <button @click="cnt++">click me+1: {{ cnt }}</button>
  </div>
</template>
<script setup>
import { ref } from 'vue'

const cnt = ref(0)
</script>
