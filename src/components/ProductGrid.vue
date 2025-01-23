<script setup>
import flowers1 from "@/assets/images/flowers1.png";
import flowers2 from "@/assets/images/flowers2.png";
import flowers3 from "@/assets/images/flowers3.png";
import item1 from "@/assets/images/item1.png";
import ProductGridItem from "./ProductGridItem.vue";
</script>
<template>
  <div class="grid border-black grid-cols-2">
    <div>
      <div class="grid grid-rows-4">
        <ProductGridItem
          title="Fresh Flowers"
          :hasTopBorder="true"
          :imageSrc="flowers2"
        />
        <ProductGridItem
          title="Live Plants"
          :hasTopBorder="true"
          :imageSrc="item1"
        />
      </div>
    </div>
    <div class="border-l border-black">
      <div class="grid grid-rows-4">
        <ProductGridItem
          title="Aroma Candles"
          :imageFirst="true"
          :imageSrc="flowers1"
        />
        <ProductGridItem
          title="Dried Flowers"
          :imageFirst="true"
          :imageSrc="flowers3"
        />
      </div>
    </div>
  </div>
</template>
