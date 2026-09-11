<script setup lang="ts">
import { computed } from 'vue'

const hideOn = new Set(['cover', 'end', 'none', 'full'])
const isHidden = computed(() => hideOn.has($nav.currentLayout ?? ''))
</script>

<template>
  <div v-if="!isHidden" class="abs-footer">
    AI Builder Sprint · {{ $nav.currentPage }}/{{ $nav.total }}
  </div>
</template>
