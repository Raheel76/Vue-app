<template>
  <div class="service"><p>Our Service</p></div>
</template>
<script>
export default {
  name: "SectionService",
};
</script>
<style scoped>
.service {
  width: 100%;
  height: 220px;
  padding: 80px, 10px, 80px, 10px;
  border: 0px, 1px, 1px, 1px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border-right: 1px solid var(--Black, #121212);
  border-bottom: 1px solid var(--Black, #121212);
  border-left: 1px solid var(--Black, #121212);
}
p {
  width: 268px;
  height: 60px;
  color: var(--Black, #121212);
  font-size: 50px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
}
</style>
