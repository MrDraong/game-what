<template>
  <div>
    <h3>{{ title }}</h3>
    <img src="" alt="" />
    <p>{{ platforms }}</p>
    <p>{{ summary }}</p>
  </div>
</template>

<script setup>
defineProps({ title, platforms, summary })
</script>
