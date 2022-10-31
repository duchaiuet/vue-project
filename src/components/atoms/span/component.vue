<template>
  <span class={{style}}>{{ label }}</span>
</template>

<script lang="ts">
export default {
  props: {
    label: String,
    style: String,
  },
};
</script>
