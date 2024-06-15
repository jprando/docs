<template>
  ... inicio: componente vue :inicio ...
  <div>
    <code>#componentevue</code>
    <div>{{ mensagem }}</div>
  </div>
  <div>
    <ContentSlot name="actions"></ContentSlot>
  </div>
  ... fim: componente vue :fim ...
</template>

<script lang="ts" setup>
defineProps<{ mensagem: string }>();
</script>

<style>

</style>