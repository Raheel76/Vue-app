<template>
  <div id="app">
    <Navbar />
    <HeroSection />
    <AboutUs />
    <SectionBenefit />
    <ContactSection />
    <SectionService />
    <ServiceSection1 />
    <ServiceSection2 />
    <SectionReviews />
  </div>
</template>

<script setup>
import Navbar from "..Navbar.vue";
import HeroSection from "..HeroSection.vue";
import AboutUs from "..AboutUs.vue";
import SectionBenefit from "..SectionBenefit.vue";
import ContactSection from "..ContactSection.vue";
import SectionService from "..SectionService.vue";
import ServiceSection1 from "..ServiceSection1.vue";
import ServiceSection2 from "..ServiceSection2.vue";
import SectionReviews from "..SectionReviews.vue";
</script>

<script>
export default {
  name: "Home",
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
#app {
  width: 1440px;
  height: 7093px;
}
</style>
