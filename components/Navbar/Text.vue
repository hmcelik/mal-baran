<template>
  <div>
    <p>{{ text }}</p>
  </div>
</template>

<style scoped>
p {
  padding: 0.7rem;
  color: black;
  width: fit-content;
  border-radius: 0.5rem;
  margin: 0 1rem 0 1rem;
  font-size: 1.2rem;
}
p:hover {
  cursor: pointer;
  background-color: rgb(223, 223, 223);
}
</style>

<script lang="ts" setup>
const props = defineProps<{
  text: String;
}>();
</script>
