<template>
  <div>
    <div class="flexdiv div1" v-if="page == 0">
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
    </div>
    <div class="flexdiv div2" v-else-if="page == 1">
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
    </div>
    <div class="flexdiv div3" v-else>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
      <div>
        <ul>
          <li><NavbarExtensionHeader text="mal baran" link="google.com" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
          <li><NavbarExtensionText text="Mal baran" link="" /></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
h5 {
  color: grey;
}
h5:hover {
  border-bottom: 1px black solid;
}
ul {
  list-style: none;
}
.flexdiv {
  display: flex;
  background-color: #fefefe;
  border-bottom: 1px solid rgb(190, 190, 190);
}
</style>

<script lang="ts" setup>
const props = defineProps<{
  page: number;
}>();
</script>
