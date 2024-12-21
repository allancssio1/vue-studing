<template>
  <div class="component">
    <h1>Component com dados reativos</h1>
    <p>Name: {{ name }} | Idade: {{ years }}</p>
    <button v-on:click="birthday">Aniversário</button>
    <button @click="changeName()">Mudar Nome</button>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const name = ref('Allan Cássio')
const years = ref(33)

function birthday() {
  years.value++
}
function changeName() {
  name.value = 'Ferreia de Freitas'
}
</script>
