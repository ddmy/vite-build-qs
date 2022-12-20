<script setup>
defineProps({
  msg: String,
  msg2: String,
  msg3: String
})
</script>

<template>
  <h1>{{ msg }}</h1>
  <h2>{{ msg2 }}</h2>
  <h3>{{ msg3 }}</h3>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
