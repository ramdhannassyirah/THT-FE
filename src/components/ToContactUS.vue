<template>
  <div class="border-y border-black">
    <div class="p-4 md:p-20 flex flex-col gap-4">
      <h1 class="text-3xl md:text-5xl font-semibold">To Contact Us</h1>
      <p>We will call you back</p>
      <div class="flex flex-col md:flex-row gap-4">
        <input
          class="border p-3 w-full"
          type="number"
          placeholder="+380 XX XXX XX XX"
        />
        <button class="bg-black px-6 py-3 text-white w-full">
          BOOK A CALL
        </button>
      </div>
    </div>
    <div  class="grid grid-cols-2 border-t  border-black">
      <div class="border-r border-black">
        <div class="text-center border-y border-black">
          <h1 class="text-2xl py-4">Phone</h1>
        </div>
        <div class="flex flex-col gap-4 items-center h-full border-r border-black justify-center  p-4">
          <p>+380980099777</p>
          <p>+380980099111</p>
        </div>
      </div>
      <div>
        <div class="text-center border-y border-black">
          <h1 class="text-2xl py-4">Address</h1>
        </div>
        <div class="flex flex-col gap-4 items-center justify-center h-full  p-4">
          <p>opening hours: 8 to 11 p.m.</p>
          <p>15/4 Khreshchatyk Street, Kyiv</p>
        </div>
      </div> 
    </div>
  </div>
  <div class="border border-black ">
    <img src="../assets/images/store.png" alt="" class="w-full" />
    <div class="grid grid-cols-2 border-t border-black ">
      <h1 class="flex gap-4 items-center text-2xl font-semibold border-black justify-center">Follow us</h1>
      <div class="flex gap-4 items-center border-l border-black justify-center p-4">
        <img src="../assets/icons/Facebook.png" alt="" class="w-4 h-4">
        <img src="../assets/icons/Instagram.png" alt=""  class="w-4 h-4">
        <img src="../assets/icons/Pinterest.png" alt=""  class="w-4 h-4">
        <img src="../assets/icons/Telegram.png" alt=""  class="w-4 h-4">
        <img src="../assets/icons/Twitter.png" alt=""  class="w-4 h-4">
      </div>
    </div>
  </div>
</template>