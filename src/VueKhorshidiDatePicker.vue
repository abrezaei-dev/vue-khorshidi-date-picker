<script setup>
import { ref } from 'vue';

const today = new Date();
const currentMonth = ref(today.getMonth() + 1);
const currentYear = ref(today.getFullYear());
</script>

<template>
  <div>
    <h2>{{ currentMonth }}/{{ currentYear }}</h2>
    <p>Your custom calendar UI goes here.</p>
  </div>
</template>

<style scoped>

</style>
