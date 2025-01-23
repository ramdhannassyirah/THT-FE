<script setup>
const features = [
  {
    title: 'Stylish bouquets by florists',
    description: 'At our floral studio, our professional florists craft the most elegant and stylish bouquets using only the freshest and highest quality materials available. We stay up-to-date with the latest floral design trends and offer unique arrangements that are sure to impress.'
  },
  {
    title: 'On-time delivery',
    description: 'Never miss a moment with our on-time flower delivery service. Our couriers will deliver your bouquet personally, without boxes, to ensure it arrives in perfect condition.'
  },
  {
    title: 'Safe payment',
    description: 'You can feel secure when placing an order with us, as we use industry-standard security measures to protect your payment information.'
  },
  {
    title: 'Subscription by your needs',
    description: 'With our subscription service tailored to your specific needs, you can enjoy the convenience of having beautiful bouquets delivered straight to your door at regular intervals.'
  }
];
</script>

<template>
  <div class="p-5 lg:p-20">
    <h1 class="text-2xl sm:text-4xl lg:text-6xl font-semibold">Why choose us?</h1>
  </div>
  <div>
    <div v-for="(feature, index) in features" :key="index" 
         class="flex p-5 lg:p-20 flex-col gap-2 sm:gap-4">
      <h1 class="text-xl sm:text-3xl lg:text-4xl">{{ feature.title }}</h1>
      <p class="text-xs sm:text-base">{{ feature.description }}</p>
    </div>
  </div>
</template>