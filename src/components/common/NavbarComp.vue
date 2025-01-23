<script setup>
import { RouterLink } from "vue-router";
</script>
<template>
  <nav>
    <!-- Mobile -->
    <div
      class="flex justify-between items-center border-b border-black lg:hidden"
    >
      <div class="">
        <img src="../../assets/icons/button.png" alt="" srcset="" />
      </div>
      <div class="">
        <img src="../../assets/icons/cart.png" alt="" srcset="" />
      </div>
    </div>

    <!-- Desktop -->
    <div class="hidden lg:grid grid-cols-4 justify-between border-b border-black">
      <!-- Kolom Kiri -->
      <div class="grid grid-cols-2">
        <div
          class="py-8 px-6 border-r text-center border-black hover:bg-gray-100 cursor-pointer"
          to="#"
        >
          Shop
        </div>
        <div
          class="py-8 px-6 border-r text-center border-black hover:bg-gray-100 cursor-pointer"
        >
          Contact
        </div>
      </div>
      <div class=""></div>
      <div class=""></div>
      <!-- Kolom Kanan -->
      <div class="grid grid-cols-2 ">
        <div
          class="py-8 px-6 border-l text-center border-black hover:bg-gray-100 cursor-pointer"
        >
          Sign in
        </div>
        <div
          class="py-8 px-6 border-l text-center border-black hover:bg-gray-100 cursor-pointer"
        >
          Cart
        </div>
      </div>
    </div>
  </nav>
</template>
