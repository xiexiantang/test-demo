<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <section id="center">
    <h1>测试功能页面</h1>
    <button class="counter" @click="count++">Count is {{ count }}</button>
  </section>
</template>
