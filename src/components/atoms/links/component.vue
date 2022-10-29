<template>
  <a :class="content1" href="href"></a>
</template>

<script>
export default {
  name: "LinkBase",
  data() {
    return {};
  },
  props: {
    label: String,
    path: {
      type: String,
      default: "square",
    },
  },
};
</script>
