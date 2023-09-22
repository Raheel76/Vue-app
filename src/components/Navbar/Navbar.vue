<template>
  <nav>
    <div class="grid grid-cols-12 gap-4">
      <div class="row-span-2">
        <NavItem text="Shop" />
        <NavItem text="Contact" />
      </div>
      <div class="col-span-6"></div>
      <div class="row-span-2">
        <NavItem text="Sign" />
        <NavItem text="Cart" />
      </div>
    </div>
  </nav>
</template>

<script>
import NavItem from "./NavItem.vue";
export default {
  name: "Navbar",
  components: {
    NavItem,
  },
};
</script>

<style scoped>
nav {
  width: 100%;
  height: 83px;
  border: 1px;
  display: flex;
  align-items: center;
  border-bottom: 1px solid var(--Black, #121212);
}
</style>
<!-- write tailwind css instead of css in navbar and firt two dives should be with
each other and other two be the same as first two and there should be space of 4
span row between first two items and last two items do this in tailwind css by
using grid system -->
