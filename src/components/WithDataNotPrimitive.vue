<template>
  <div class="component">
    <h1>Component com dados reativos não primitivos</h1>
    <p>Name: {{ people.name }} | Idade: {{ people.years }}</p>
    <button @click="birthday">Aniversário</button>
    <button @click="changeName()">Mudar Nome</button>
  </div>
</template>

<!-- <script setup>
import { reactive } from 'vue'

const people = reactive({
  name: 'Allan Cássio',
  years: 33,
})

function birthday() {
  people.years++
}
function changeName() {
  people.name = 'Ferreia de Freitas'
}
</script> -->
<script>
export default {
  data: function () {
    return {
      pessoa: {
        name: 'Allan Cássio',
        years: 33,
      },
    }
  },
  methods: {
    birthday: function () {
      this.pessoa.years++
    },
    changeName: function () {
      this.pessoa.name = 'Ferreira de Freitas'
    },
  },
}
</script>
