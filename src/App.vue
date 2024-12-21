<script setup>
import FirstComponent from './components/FirstComponent.vue'
import WithDatas from './components/WithDatas.vue'
import WithDataPrimitive from './components/WithDataPrimitive.vue'
import WithDataNotPrimitive from './components/WithDataNotPrimitive.vue'
</script>

<template>
  <header>Vue</header>
  <WithDataNotPrimitive />
  <WithDataPrimitive />
  <WithDatas />
  <FirstComponent />
</template>

<style scoped></style>
