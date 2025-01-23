<script setup>
defineProps({
  title: {
    type: String,
    required: true,
  },
  imageSrc: {
    type: String,
    required: true,
  },
  hasTopBorder: {
    type: Boolean,
    default: false,
  },
  imageFirst: {
    type: Boolean,
    default: false,
  },
});
</script>

<template>
  <template v-if="!imageFirst">
    <div
      class="flex flex-col justify-center items-center border-b border-black p-2 sm:p-4"
    >
      <div class="flex justify-center items-center h-full">
        <h1 class="text-sm sm:text-2xl lg:text-4xl text-center">{{ title }}</h1>
      </div>
      <div class="">
        <p class="inline-flex items-center gap-2 font-semibold">
          Shop now
          <span><img src="../assets/icons/arrow-right.png" alt="" /></span>
        </p>
      </div>
    </div>
    <div class="overflow-hidden lg:h-auto">
      <img :src="imageSrc" class="w-full object-cover" :alt="title" />
    </div>
  </template>
  <template v-else>
    <div class="overflow-hidden lg:h-auto">
      <img :src="imageSrc" class="w-full object-cover" :alt="title" />
    </div>
    <div
      class="flex flex-col justify-center items-center border-b border-black p-2 sm:p-4"
    >
      <div class="flex justify-center items-center h-full">
        <h1 class="text-sm sm:text-2xl lg:text-4xl text-center">{{ title }}</h1>
      </div>
      <div class="">
        <p class="inline-flex items-center gap-2 font-semibold">
          <span><img src="../assets/icons/arrow-left.png" alt="" /></span>
          Shop now
        </p>
      </div>
    </div>
  </template>
</template>
