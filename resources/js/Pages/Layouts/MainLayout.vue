<template>
  <div>Index</div>
  <Link href="/">Home</Link>
  <Link href="/show">Show</Link>
  <Link href="/listing/create">Create</Link>
  <div>The Time {{ timer }}</div>
  <slot />
</template>

<script setup>
import {Link} from '@inertiajs/vue3'
import { ref } from 'vue'
const timer = ref(0)
// setInterval(() => timer.value++,100)
</script>