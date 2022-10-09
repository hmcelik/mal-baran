<template>
  <div>
    <button>{{ text }}</button>
  </div>
</template>

<style scoped>
button {
  padding: 1rem;
  background-color: v-bind("color");
  border-radius: 0.5rem;
  font-size: 1rem;
  color: white;
  margin: 0 1rem 0 1rem;
  border: none;
}
button:hover {
  cursor: pointer;
}
</style>

<script lang="ts" setup>
const props = defineProps<{
  text: String;
  color: String;
}>();
</script>
