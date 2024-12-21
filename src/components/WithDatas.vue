<template>
  <div>
    <h1>Component com Dadaos</h1>
    <p>Nome: {{ productName }} {{ code }}</p>
  </div>
</template>

<style scoped>
div {
  text-align: center;
  border: 2px solid rgb(10, 69, 4);
  background-color: #060d05;
  border-radius: 15px;
  margin: 30px;
  padding: 10px;
}
p {
  font-size: 1.2rem;
}
</style>

<script setup>
const productName = 'Borracha'
const code = '#456'
</script>
<!-- <script>
// optional API
// export default {
//   data: function () {
//     return {
//       productName: 'caderrno',
//       code: '#321',
//     }
//   },
// }

// composition API
// export default {
//   setup: function () {
//     const productName = 'lapis'
//     const code = '#789'
//     return { productName, code }
//   },
// }
</script> -->
