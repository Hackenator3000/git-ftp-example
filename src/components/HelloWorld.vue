<script setup lang="ts">
import { ref } from "vue"

interface Props {
  message: string;
}

const props = defineProps<Props>();

const count = ref(0)
</script>

<template>
  <h1>{{ props.message }}</h1>

  <div class="card">
    <p>
      builded and deployed
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
