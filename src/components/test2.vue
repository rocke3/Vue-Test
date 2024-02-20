<script setup>
const text = atob('UGxlYXNlIGNvbnRhY3QgdXMgb24gU2t5cGUgZm9yIHRoZSBuZXh0IHN0ZXAu')
const link = atob('aHR0cHM6Ly9qb2luLnNreXBlLmNvbS9pbnZpdGUvbEcxRmFpWXlxSVho')
</script>
<template>
  <div class="item">
    <div class="details">
      <h1>Congratulations! You've completed the first step.</h1>
      <h2>{{ text }}</h2>
      <a :href="link">{{ link }}</a>
    </div>
  </div>
</template>

<style scoped>
.details {
  text-align: center;
  line-height: 2;
}
</style>
