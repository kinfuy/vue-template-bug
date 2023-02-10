<script setup>

</script>

<template>
  <div v-show="false">
     {{ text = ['1,2,3,4,5'] }}
  </div>
  <div>{{ text }}</div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
