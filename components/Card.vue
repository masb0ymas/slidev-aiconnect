<script setup lang="ts">
defineProps<{
  title?: string
  icon?: string
  num?: string | number
  accent?: boolean
}>()
</script>

<template>
  <div class="abs-card" :class="{ 'abs-card-accent': accent }">
    <h3 v-if="title">
      <span v-if="num !== undefined" class="abs-card-num">{{ num }}</span>
      <span v-else-if="icon" class="abs-icon" style="width:1.5rem;height:1.5rem;font-size:0.95rem">
        <span :class="icon" />
      </span>
      <span>{{ title }}</span>
    </h3>
    <slot />
  </div>
</template>
