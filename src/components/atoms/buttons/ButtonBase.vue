<template>
  <button :class="shape">{{ label }}</button>
</template>

<script>
export default {
  name: "ButtonBase",
  data() {
    return {};
  },
  props: {
    label: String,
    shape: {
      type: String,
      default: "square",
    },
    style: {
      type: String,
      default: "square",
    },
  },
};
</script>
