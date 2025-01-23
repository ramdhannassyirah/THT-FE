<template>
  <footer>
    <div class="grid grid-cols-2 lg:grid-cols-4 border border-black ">
      <div class="flex flex-col gap-4 border-r border-b border-black p-6">
        <p>
          Remember to offer beautiful flowers from Kyiv LuxeBouquets Valentines
          Day, Mothers Day, Christmas... Reminds you 7 days before. No spam or
          sharing your address
        </p>
        <input
          class="border p-3  w-full"
          type="number"
          placeholder="Your Mail"
        />
        <button class="bg-black px-6 py-3 text-white w-full">
          REMIND
        </button>
      </div>
      <div class="flex border-b  flex-col gap-4 border-r border-black p-6">
        <p class="title text-lg">Contact Us</p>
        <div class="">
          <p class="title">Address</p>
          <p>15/4 Khreshchatyk Street, Kyiv</p>
        </div>
        <div class="">
          <p class="title">Phone</p>
          <p>+380980099777</p>
        </div>
        <div class="break-all">
          <p class="title">General Enquiry:</p>
          <p>Kiev.Florist.Studio@gmail.com</p>
        </div>
        <div class="flex  flex-col gap-4">
          <p class="title text-lg">Follow Us</p>
          <div class="flex flex-wrap gap-4">
            <img src="../../assets/icons/Facebook.png" alt="" class="w-6 h-6" />
            <img
              src="../../assets/icons/Instagram.png"
              alt=""
              class="w-6 h-6"
            />
            <img
              src="../../assets/icons/Pinterest.png"
              alt=""
              class="w-6 h-6"
            />
            <img src="../../assets/icons/Telegram.png" alt="" class="w-6 h-6" />
            <img src="../../assets/icons/Twitter.png" alt="" class="w-6 h-6" />
          </div>
        </div>
      </div>
      <div class="flex flex-col gap-4 border-r border-black p-6">
        <p class="title text-lg">Shop</p>
        <div class="">
          <p>All Products</p>
          <p>Fresh Flowers</p>
          <p>Live Plants</p>
          <p>Designer Vases</p>
          <p>Aroma Candles</p>
          <p>Freshener Diffuser</p>
        </div> 
            <p class="title text-lg ">Service</p>
            <div class="">
                <p>Flower Subcription</p>
                <p>Wedding & Event Decor</p>
            </div>
      </div>
      <div class="flex flex-col gap-4 border-r border-black p-6">
        <p class="title text-lg">About Us</p>
        <div class="">
            <p>Our story</p>
            <p>Blog</p>
        </div>
        <div class="">
            <p>Shipping & returns</p>
            <p>Terms & conditions</p>
            <p>Privacy policy</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.title {
    color: gray;
}

</style>
