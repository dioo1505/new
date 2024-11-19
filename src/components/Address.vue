<template>
  <div class="bg-[#00B534] h-[82px] flex align-center justify-center mt-[58px]">
    <h1
      class="pt-[19px] font-extrabold text-[#fff] text-[33px] leading-[42.9px]"
    >
      Manzil
    </h1>
  </div>
  <div class="flex">
    <div class="w-[50%] h-[100%] relative">
      <img class="w-[100%]" :src="pdp" alt="pdp" />
      <div>
        <div
          class="w-[522px] h-[106px] rounded-[40px] bg-[#fff] flex align-center gap-[18px] absolute top-[450px] left-[80px] py-[9px] px-[46px] shadow-[0_2px_10px_0_#012A304D]"
        >
          <img class="w-[88px] h-[88px]" :src="loggo" alt="loggo" />
          <p
            class="text-[23px] text-[#00282F] leading-[29.9px] font-medium pt-[15px]"
          >
            Toshkent sh., Shayxontohur tum., Beruniy ko’ch., 3A-uy
          </p>
        </div>
      </div>
    </div>
    <div class="w-[50%]">
      <img class="w-[100%]" :src="map" alt="map" />
    </div>
  </div>
</template>

<script setup>
import pdp from "../assets/img/pdp.png";
import map from "../assets/img/map.png";
import loggo from "../assets/img/loggo.png";
</script>
