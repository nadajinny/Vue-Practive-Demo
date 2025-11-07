<template>
  <div>Hello, {{ message }}</div>
</template>

<script lang="ts">
export default {
  name: 'E01Instance',
};
</script>

<script setup lang="ts">
import { ref } from 'vue';

const message = ref('Vue!');
</script>

<style scoped>
div {
  color: blue;
}
</style>
