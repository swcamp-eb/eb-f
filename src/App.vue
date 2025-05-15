<template>
  <div>
    <button v-on:click="move">무브무브</button>
  </div>
</template>

<script setup>
  function move() {
    location.href='https://naver.com';
  }
</script>