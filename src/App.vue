<script setup>
import FirstComponent from './components/FirstComponent.vue'
import WithDatas from './components/WithDatas.vue'
import WithDataPrimitive from './components/WithDataPrimitive.vue'
import WithDataNotPrimitive from './components/WithDataNotPrimitive.vue'
import DataBinding from './components/DataBinding.vue'
</script>

<template>
  <header>Vue</header>
  <DataBinding />
  <WithDataNotPrimitive />
  <WithDataPrimitive />
  <WithDatas />
  <FirstComponent />
</template>

<style scoped></style>
