<template>
  <header
    class="bg-slate-800 py-5 bg-gradient-to-r from-[#012A30] via-[#012A30] via-43% to-[#00b533c5] to-80%"
  >
    <div class="max-w-[992px] px-2 mx-auto">
      <div class="flex items-center">
        <a href="" class="mr-8 block">
          <img class="w-[100px] h-6" :src="headerLogo" alt="header logo" />
        </a>

        <nav>
          <ul class="flex items-center gap-5">
            <li>
              <a class="text-[rgba(136,240,54,1)] decoration-none" href=""
                >Kurslarimiz</a
              >
            </li>
            <li>
              <a class="text-[rgba(136,240,54,1)] decoration-none" href=""
                >Bog’lanish</a
              >
            </li>
          </ul>
        </nav>

        <div class="ml-auto">
          <a href="" class="flex items-center gap-2 text-white">
            <svg
              width="21"
              height="21"
              viewBox="0 0 21 21"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g clip-path="url(#clip0_4_23)">
                <path
                  d="M6.76348 1.00894C6.44766 0.24605 5.61504 -0.160005 4.81934 0.0573777L1.20996 1.04175C0.496289 1.23863 0 1.88667 0 2.62496C0 12.7722 8.22773 21 18.375 21C19.1133 21 19.7613 20.5037 19.9582 19.79L20.9426 16.1806C21.16 15.3849 20.7539 14.5523 19.991 14.2365L16.0535 12.5959C15.385 12.3169 14.6098 12.5097 14.1545 13.0716L12.4975 15.0937C9.60996 13.7279 7.27207 11.39 5.90625 8.50249L7.92832 6.84957C8.49023 6.39019 8.68301 5.6191 8.4041 4.95054L6.76348 1.01304V1.00894Z"
                  fill="white"
                />
              </g>
              <defs>
                <clipPath id="clip0_4_23">
                  <rect width="21" height="21" fill="white" />
                </clipPath>
              </defs>
            </svg>
            (78) 777-47-47
          </a>
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import headerLogo from "../assets/icon/header-logo.svg";
</script>

<style lang="scss" scoped></style>
