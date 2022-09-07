<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <div class="card">
    <button type="button" @click="count += 10">count is {{ count }}</button>
  </div>
</template>

<style scoped></style>
