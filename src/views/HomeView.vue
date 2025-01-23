<script setup>
import HeroSection from "@/components/HeroSection.vue";
import ProductGrid from "@/components/ProductGrid.vue";
import AboutSection from "@/components/AboutSection.vue";
import WhyChooseUs from "@/components/WhyChooseUs.vue";
import ToContactUS from "@/components/ToContactUS.vue";
import OurServices from "@/components/OurServices.vue";
</script>

<template>
    <div class="grid grid-cols-1 lg:grid-cols-2">
      <HeroSection />
      <ProductGrid />
    </div>
    <div class="grid grid-cols-1 lg:grid-cols-2">
      <AboutSection />
      <WhyChooseUs />
    </div>
    <div class="grid grid-cols-1 lg:grid-cols-2">
      <ToContactUS />
    </div>
    <div class="grid grid-cols-1 lg:grid-cols-2 ">
      <OurServices />
    </div>
</template>
