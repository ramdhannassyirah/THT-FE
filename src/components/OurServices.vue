<template>
  <div class="col-span-2 p-20">
    <h1 class="text-center text-4xl lg:text-6xl font-semibold">Our Services</h1>
  </div>
  <div class="border-y border-black">
    <img src="../assets/images/subscription.png" alt="" />
  </div>

  <div class="border-y border-black">
    <div
      class="flex flex-col gap-4 justify-center items-center md:p-20 p-6 h-full"
    >
      <p class="text-lg">service</p>
      <h1 class="text-4xl font-semibold">Flower Subcriptions</h1>
      <p class="text-center text-lg">
        Experience the convenience and savings of regular flower deliveries with
        our flexible subscription service - up to 30% more profitable than
        one-time purchases.
      </p>
      <button class="px-6 py-4 border border-black mt-10">SUBSCRIBE NOW</button>
    </div>
  </div>

  <!-- Wedding -->
  <div class="col-span-2">
    <div class="relative">
      <img src="../assets/images/wedding.jpg" class="h-full w-full" alt="" />
      <div class="absolute top-0 left-0 w-full h-full bg-black/50 z-50">
        <div
          class="flex flex-col justify-center gap-4 items-center h-full text-white"
        >
          <p>SERVICE</p>
          <h1 class="text-4xl text-center font-semibold">
            Wedding & Event Decor
          </h1>
          <p class="text-center px-4">
            Let our team of expert florists and designers create stunning,
            on-trend floral décor for your special day. Trust us to bring your
            vision to life.
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- Client Say -->
  <div class="col-span-2 p-20">
    <div class="relative">
      <div
        class="w-full h-full lg:flex justify-between items-center lg:absolute hidden"
      >
        <img src="../assets/icons/leftArrow.png" alt="" />
        <img src="../assets/icons/rightArrow.png" alt="" />
      </div>
      <div class="flex flex-col justify-center items-center gap-4">
        <div class="">
          <img src="../assets/images/googleLogo.png" alt="" />
        </div>
        <p>REVIEWS</p>
        <h1 class="text-4xl font-semibold">Our Client Say</h1>
        <p class="lg:text-xl text-center w-[80%]">
          “Ordered flowers online and they were the best bouquet! Impressed
          everyone around. Highly recommend this flower shop!”
        </p>
        <p>– Ronald Richards</p>
        <button class="px-6 py-4 border border-black mt-10">
          READ REVIEWS
        </button>
      </div>
    </div>
  </div>
</template>
