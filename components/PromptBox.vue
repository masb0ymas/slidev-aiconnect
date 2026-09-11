<script setup lang="ts">
defineProps<{
  label?: string
  /** 'neutral' | 'bad' | 'good' */
  tone?: 'neutral' | 'bad' | 'good'
}>()
</script>

<template>
  <div class="abs-prompt">
    <div
      class="abs-prompt-label"
      :class="{ 'is-bad': tone === 'bad', 'is-good': tone === 'good' }"
    >
      <span v-if="tone === 'bad'" class="i-carbon-close-outline" />
      <span v-else-if="tone === 'good'" class="i-carbon-checkmark" />
      <span v-else class="i-carbon-terminal" />
      {{ label ?? 'Prompt' }}
    </div>
    <div class="abs-prompt-body">
      <slot />
    </div>
  </div>
</template>
