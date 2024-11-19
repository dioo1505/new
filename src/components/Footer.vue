<template>
  <div class="bg-[#012a30] h-[170px]">
    <div class="flex align-center justify-between py-[39px] px-[143px]">
      <img class="w-[138px] h-[38px]" :src="footerLogo" alt="" />
      <div class="flex align-center gap-[10px]">
        <div
          class="w-[32px] h-[32px] rounded-[50%] bg-[#00B534] flex align-center justify-center"
        >
          <img class="w-[17px]" :src="telegram" alt="telegram" />
        </div>
        <div
          class="w-[32px] h-[32px] rounded-[50%] bg-[#00B534] flex align-center justify-center"
        >
          <img class="w-[17px]" :src="instagram" alt="instagram" />
        </div>
        <div
          class="w-[32px] h-[32px] rounded-[50%] bg-[#00B534] flex align-center justify-center"
        >
          <img class="w-[17px]" :src="youtube" alt="youtube" />
        </div>
      </div>
      <span class="text-[#DBF9D8] leading-[26px] font-bold text-[20px]"
        >(78) 777-47-47</span
      >
    </div>
    <hr class="mx-[143px]" />
    <div class="flex align-center justify-between px-[143px] pt-[17px]">
      <span class="text-[#DBF9D8] text-[12px] leading-[15.6px] font-normal"
        >©2022 PDP Academy</span
      >
      <span class="text-[#DBF9D8] text-[12px] leading-[15.6px] font-normal"
        >Xizmatlar litsenziyalangan</span
      >
    </div>
  </div>
</template>

<script setup>
import footerLogo from "../assets/icon/header-logo.svg";
import telegram from "../assets/icon/telegram.svg";
import instagram from "../assets/icon/instagram.svg";
import youtube from "../assets/icon/youtube.svg";
</script>

<style scoped lang="scss"></style>
