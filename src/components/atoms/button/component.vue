<template>
  <button type="{{ type }}" class="{{ className }}">{{ label }}</button>
</template>

<script lang="ts">
export default {
  props: {
    type: String,
    label: String,
    className: String,
  },
};
</script>
