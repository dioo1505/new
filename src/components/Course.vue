<template>
  <div
    class="bg-[#00B534] h-[82px] font-bold text-white flex items-center justify-center"
  >
    <h2 class="text-center text-[33px]">
      Bizning kurslarimiz kimga to’g’ri keladi ?
    </h2>
  </div>

  <div class="h-[688px] mt-10">
    <div class="max-w-[992px] mx-auto">
      <div class="flex justify-between gap-350">
        <div class="">
          <img
            class="rounded-lg w-[700px] h-[546px]"
            :src="courseTarget"
            alt="course target bg"
          />
        </div>

        <div class="relative">
          <div
            class="border w-[586px] h-[546px] px-[34px] py-[33px] rounded-2xl bg-white relative z-10"
          >
            <h3 class="font-bold text-[26px] leading-8 mb-2 text-[#001122]">
              Asosan 8 -17 yoshdagi bolalar uchun
            </h3>

            <p class="font-normal text-[21px] text-[#012A30] mb-[63px]">
              Bolarda dasturlash yo’nalishiga birinchi qadam tashlash, kompyuter
              savodxonligini oshirish, mantiqiy fikrlashni kengaytirish,
              matematik bilimlarni takomillashtirish.
            </p>

            <h3 class="text-[26px] font-bold mb-2">
              Farzandiga befarq boʻlmagan ota-onalar
            </h3>

            <ul class="list-disc pl-6">
              <li class="mb-4 text-[21px]">
                Farzandining til oʻrganishini xohlaydigan va bunga sharoit
                yaratib beradigan.
              </li>

              <li class="mb-4 text-[21px]">
                Kelajakda farzandining katta yutuqlaridan faxrlanib yurishni
                istagan.
              </li>

              <li class="text-[21px]">
                Farzandining kelajagi uchun hozirdan bilimga investitsiya
                qiladigan ota-onalar uchun moʻljallangan.
              </li>
            </ul>
          </div>

          <!-- Absolute joylashuvli element -->
          <div
            class="w-[586px] h-[586px] bg-[#DBF9D8] absolute top-0 left-0 z-0 rotate-6 rounded-[21px]"
          ></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import courseTarget from "../assets/img/image 2.png";
</script>

<style scoped lang="scss"></style>
