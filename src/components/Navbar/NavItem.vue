<template>
  <div class="nav-link">
    {{ text }}
  </div>
</template>

<script>
export default {
  name: "NavItem",
  props: {
    text: {
      type: String,
      default: "",
    },
  },
};
</script>

<style scoped>
.nav-link {
  border: 1px solid black;
  padding: 24px 62px;
  height: 43%;
}
</style>
