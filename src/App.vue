<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <main>
    <h1>🐾 MyPet TEST AI</h1>
    <button @click="count++">Count: {{ count }}</button>
  </main>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem;
  font-family: sans-serif;
}
button {
  margin-top: 1rem;
  padding: 0.5rem 1.5rem;
  font-size: 1rem;
  cursor: pointer;
}
</style>
