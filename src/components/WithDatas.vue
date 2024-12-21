<template>
  <div class="component">
    <h1>Component com Dadaos</h1>
    <p>Nome: {{ productName }} {{ code }}</p>
  </div>
</template>

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
