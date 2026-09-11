<script setup lang="ts">
defineProps<{
  /** Langkah yang sedang aktif, 1-based */
  active?: number
  steps?: string[]
}>()

const defaultSteps = ['Ide', 'Spesifikasi', 'Instruksi', 'Bangun', 'Uji']
</script>

<template>
  <div class="abs-flow">
    <div
      v-for="(label, i) in (steps ?? defaultSteps)"
      :key="label"
      class="abs-flow-item"
      :class="{ 'is-active': active === i + 1 }"
    >
      <span class="opacity-60 mr-1">{{ i + 1 }}.</span>{{ label }}
    </div>
  </div>
</template>
