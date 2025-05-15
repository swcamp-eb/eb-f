<template>
  <div>
    <!-- <input type="text" v-model="test" placeholder=".shop주소 도메인을 입력하세요"> -->
    <button v-on:click="move">무브무브</button>
  </div>
</template>

<script setup>
  // import {ref} from 'vue';

  // const test = ref('');

  function move() {
    // location.href='https://' + test + '.shop';
    location.href='https://naver.com';
  }
</script>