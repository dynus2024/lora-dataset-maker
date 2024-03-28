<script setup lang="ts">
import { onMounted } from 'vue';
import { initFlowbite } from 'flowbite';

onMounted(() => {
  initFlowbite();
})
</script>

<template>
  <div class="bg-slate-200 rounded font-bold font-serif p-4 m-4">Hello</div>
</template>
