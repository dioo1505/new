<template>
  <div class="h-[82px] bg-[#00B534] flex align-center justify-center pt-[19px]">
    <h2 class="text-[#fff] font-extrabold text-[33px] leading-[42.9px]">
      PDP Junior kurslari
    </h2>
  </div>

  <div class="max-w-[992px] mx-auto">
    <div class="relative mt-24">
      <div
        class="border w-[992px] h-[312px] mt-[88px] rounded-[31px] bg-white relative z-10 flex align-center gap-[83px]"
      >
        <div>
          <img :src="roboto" alt="roboto" />
        </div>

        <div class="flex flex-col justify-center">
          <div class="flex gap-[10px] mb-[11px]">
            <h2 class="font-bold text-[33px] text-[#012A30] leading-[42.9px]">
              Robototexnika
            </h2>
            <button
              class="w-[92px] h-[40px] bg-[#00B534] rounded-[67px] text-[#fff] text-[20px] leadimg-[31.2px]"
            >
              Yangi
            </button>
          </div>
          <p
            class="font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            - Robot elektronikasini yig’ishni
          </p>
          <p
            class="font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            - Robotlarga erkin dastur yozish C++ tilida
          </p>
          <p
            class="font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            - Motorlar va Sensorlarni ishlata olish
          </p>
          <p
            class="font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            - Korpuslarni 3D ko’rinishda yaratish
          </p>
          <div class="flex mt-[30.5px] gap-[54px]">
            <div class="flex flex-col">
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Davomiligi
              </h3>
              <span
                class="block text-center text-[26px] text-[#00B534] leading-[33.8px] font-extrabold"
                >8 oy</span
              >
            </div>
            <div>
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Yosh chegarasi
              </h3>
              <span
                class="block text-[26px] text-[#00B534] leading-[33.8px] font-extrabold text-center"
                >10 - 17</span
              >
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[992px] h-[312px] bg-[#DBF9D8] absolute top-0 left-0 z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>

    <div class="relative mt-24">
      <div
        class="border w-[992px] h-[312px] mt-[88px] rounded-[31px] bg-white relative z-10 flex align-center gap-[160px]"
      >
        <div class="pt-[53.88px] pl-[77.44px]">
          <img :src="frontend" alt="frontend" />
        </div>

        <div class="flex flex-col justify-center">
          <div class="flex gap-[10px] mb-[11px]">
            <h2 class="font-bold text-[33px] text-[#012A30] leading-[42.9px]">
              Frontend
            </h2>
          </div>
          <p
            class="w-[572px] font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            Frontend development kursi pdp kids loyihasining yosh jihatidan
            uchinchi kursi hisoblanadi. Bu kursda o’quvchilar  web sahifalarning
            bizga ko'rinadigan vizual qismini yaratishadi.
          </p>

          <div class="flex mt-[30.5px] gap-[54px]">
            <div class="flex flex-col">
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Davomiligi
              </h3>
              <span
                class="block text-center text-[26px] text-[#00B534] leading-[33.8px] font-extrabold"
                >10 oy</span
              >
            </div>
            <div>
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Yosh chegarasi
              </h3>
              <span
                class="block text-[26px] text-[#00B534] leading-[33.8px] font-extrabold text-center"
                >10 - 14</span
              >
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[992px] h-[312px] bg-[#DBF9D8] absolute top-0 left-0 z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>

    <div class="relative mt-24">
      <div
        class="border w-[992px] h-[312px] mt-[88px] rounded-[31px] bg-white relative z-10 flex align-center gap-[83px]"
      >
        <div class="pt-[10px] pl-[10px]">
          <img :src="python" alt="python" />
        </div>

        <div class="flex flex-col justify-center">
          <div class="flex gap-[10px] mb-[11px]">
            <h2 class="font-bold text-[33px] text-[#012A30] leading-[42.9px]">
              Python
            </h2>
          </div>
          <p
            class="w-[572px] font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            Bolalar Python dasturlash tili misolida boshlang'ich dasturlash
            asoslarini mukammal o'rganishib bilim va ko'nikmalar hosil qiladi.
            Dasturlash sohasining asosiy tushunchalarini mustahkamlagan holda
            farzandingizda yangi bilim va ko'nikmalarni hosil qiladi.
          </p>

          <div class="flex mt-[30.5px] gap-[54px]">
            <div class="flex flex-col">
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Davomiligi
              </h3>
              <span
                class="block text-center text-[26px] text-[#00B534] leading-[33.8px] font-extrabold"
                >11 oy</span
              >
            </div>
            <div>
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Yosh chegarasi
              </h3>
              <span
                class="block text-[26px] text-[#00B534] leading-[33.8px] font-extrabold text-center"
                >8 - 14</span
              >
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[992px] h-[312px] bg-[#DBF9D8] absolute top-0 left-0 z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>

    <div class="relative mt-24">
      <div
        class="border w-[992px] h-[312px] mt-[88px] rounded-[31px] bg-white relative z-10 flex align-center gap-[115px]"
      >
        <div class="pt-[131px] pl-[69px]">
          <img :src="scratch" alt="python" />
        </div>

        <div class="flex flex-col justify-center">
          <div class="flex gap-[10px] mb-[11px]">
            <h2 class="font-bold text-[33px] text-[#012A30] leading-[42.9px]">
              Scratch development
            </h2>
          </div>
          <p
            class="w-[572px] font-normal text-[18px] leading-[23.4px] tracking-[4%] text-[#012A30]"
          >
            Scratch development kursi pdp kids loyihasining yosh jihatidan
            ikkinchi kursi hisoblanadi. Kompyuter savodxonligiga ega bo'lgan
            jajji dasturchilar uchun kirish kursi hisoblandi. Oddiy dasturlash
            kurslaridan farqli o'laroq qiziqarli rang-barang bloklar bilan
            o'rgatiladi.
          </p>

          <div class="flex mt-[30.5px] gap-[54px]">
            <div class="flex flex-col">
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Davomiligi
              </h3>
              <span
                class="block text-center text-[26px] text-[#00B534] leading-[33.8px] font-extrabold"
                >9 oy</span
              >
            </div>
            <div>
              <h3
                class="font-semibold text-[#001122] leading-[29.9px] text-[23px]"
              >
                Yosh chegarasi
              </h3>
              <span
                class="block text-[26px] text-[#00B534] leading-[33.8px] font-extrabold text-center"
                >8 - 12</span
              >
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[992px] h-[312px] bg-[#DBF9D8] absolute top-0 left-0 z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>
  </div>
</template>

<script setup>
import roboto from "../assets/img/roboto.png";
import frontend from "../assets/img/Frontend.png";
import python from "../assets/img/python.png";
import scratch from "../assets/img/scratch.png";
</script>

<style scoped lang="scssclass=" mb-4 text-[21px] leading-[27.3px]></style>
