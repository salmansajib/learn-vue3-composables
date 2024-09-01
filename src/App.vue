<script setup>
import { useMouse } from "./mouse";

const { x, y } = useMouse();
</script>

<template>
  <h1 class="text-4xl">Vue3 Composables</h1>

  <div>
    <h2>Track Mouse Position</h2>
    <p>Position X: {{ x }}</p>
    <p>Position Y: {{ y }}</p>
  </div>
</template>
