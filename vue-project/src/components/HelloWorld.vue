<script setup>
import {ref} from 'vue';

let counter = ref(0);

function inc() {
  counter.value++;
}

</script>

<template>
  <div class="greetings">
  <h1>Hello</h1>
  {{ counter }}
    <button @click="inc"> Increment</button>
  </div>
</template>

<style scoped>
</style>
