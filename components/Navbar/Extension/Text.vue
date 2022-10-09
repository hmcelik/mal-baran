<template>
  <div>
    <h4>
      <a :href="link">{{ text }}</a>
    </h4>
  </div>
</template>

<style scoped>
h4 {
  width: fit-content;
}
h4:hover {
  text-decoration: underline;
}
a {
  text-decoration: none;
  color: black;
}
</style>

<script lang="ts" setup>
const props = defineProps<{
  text: String;
  link: String;
}>();
</script>
