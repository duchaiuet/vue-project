<template>
  <input
    type="{{ type }}"
    v-bind:class="className"
    v-bind:placeholder="placeholder"
  />
</template>

<script lang="ts">
export default {
  props: {
    type: String,
    placeholder: String,
    className: String,
  },
  data() {
    return {};
  },
};
</script>
