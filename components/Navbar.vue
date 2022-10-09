<template>
  <div>
    <div class="navbar">
      <div class="left-items items">
        <img class="logo" src="../images/logo.png" alt="" />
        <NavbarText text="Mal Baran" @mouseover="hover = 0" />
        <NavbarText text="Mal Baran" @mouseover="hover = 1" />
        <NavbarText text="Mal Baran" @mouseover="hover = 2" />
      </div>
      <div class="right-items items">
        <NavbarButton text="Mal Baran" color="orange" />
        <NavbarButton text="Mal Baran" color="green" />
      </div>
    </div>
    <div class="extension">
      <NavbarExtension v-if="hover == 0" :page="hover" />
      <NavbarExtension v-else-if="hover == 1" :page="hover" />
      <NavbarExtension v-else :page="hover" />
    </div>
  </div>
</template>

<style scoped>
.navbar {
  background-color: v-bind("color");
  width: 100%;
  height: 8rem;
  position: fixed;
  display: flex;
  justify-content: space-between;
  width: 100%;
  border-bottom: 1px solid rgb(190, 190, 190);
}

.extension:hover {
  display: block;
}

.extension {
  padding-top: 8rem;
  display: none;
}

.navbar:hover + .extension {
  display: block;
}

.items {
  display: flex;
  justify-content: center;
  align-items: center;
}
img {
  margin: 1rem;
  height: 5rem;
}
</style>

<script lang="ts" setup>
import Extension from "./Navbar/Extension.vue";
const props = defineProps<{
  color: String;
}>();

let show = ref<String>("none");
let hover = ref<number>(0);
</script>
