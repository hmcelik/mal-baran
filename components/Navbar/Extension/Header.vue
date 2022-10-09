<template>
  <div class="maindiv">
    <h3>
      <a :href="link">{{ text }}</a>
    </h3>
    <img src="../../../images/up-arrow.png" alt="" />
  </div>
</template>

<style scoped>
.maindiv {
  display: flex;
  flex-direction: row;
  align-items: center;
}
h3:hover {
  text-decoration: underline;
  width: max-content;
}
img {
  height: 1rem;
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
