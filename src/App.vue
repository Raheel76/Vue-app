<template>
  <div id="app1">
    <Navbar />
    <HeroSection />
    <AboutUs />
    <SectionBenefit />
    <ContactSection />
    <SectionService />
    <ServiceSection1 />
    <ServiceSection2 />
    <SectionReviews />
    <Home />
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar/Navbar.vue";
import HeroSection from "./components/HeroSection.vue";
import AboutUs from "./components/AboutUs.vue";
import SectionBenefit from "./components/SectionBenefit.vue";
import ContactSection from "./components/ContactSection.vue";
import SectionService from "./components/SectionService.vue";
import ServiceSection1 from "./components/ServiceSection1.vue";
import ServiceSection2 from "./components/ServiceSection2.vue";
import SectionReviews from "./components/SectionReviews.vue";
</script>

<script>
export default {
  name: "App",
  components: {
    Navbar,
    HeroSection,
    AboutUs,
    SectionBenefit,
    ContactSection,
    SectionService,
    ServiceSection1,
    ServiceSection2,
    SectionReviews,
  },
};
</script>
<style scoped>
/* body {
  width: 1440px;
  height: 7093px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
} */

/* template {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
} */
#app1 {
  width: 100%;
  height: 7093px;
  /* top: 300px; */
  /* left: 300px; */
  display: inline-flex;
  flex-direction: column;

  border: 1px solid var(--Black, #121212);
  background: var(--White, #fff);
}
</style>
