<script lang="ts" setup>
const data = ref({
  title: 'ABC',
  value: 'ABVC'
})


</script>

<template>

<div>

  ABC XASDASD
   <slot name="abc" :data="data" />
</div>
</template>