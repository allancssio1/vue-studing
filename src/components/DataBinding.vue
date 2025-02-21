<template>
  <div class="component">
    <h1>Component com data binding</h1>
    <input type="text" v-bind:value="valueInput" ></input>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const valueInput = ref('Aprendendo VueJs')
</script>
