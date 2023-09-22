<template>
  <div class="nav-links">
    {{ text }}
  </div>
</template>

<script>
export default {
  name: "MainNav",
};
</script>

<style scoped>
.nav-links {
  display: flex;
  align-items: flex-start;
  cursor: pointer;
  border-right: 1px solid var(--Black, #121212);
}
.text {
  width: 180px;
  height: 83px;
  padding: 32px, 24px, 32px, 24px;
  border: 0px, 1px, 0px, 0px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-right: 1px solid var(--Black, #121212);
}
</style>
