<template>
  <div class="mt-[38px] md:flex items-center justify-between">
    <div>
      <div><img src="@/assets/images/logo2.svg" alt="logo"></div>
      <div class="mt-6 mb-3">
        <h4 class="font-bold text-[32px] leading-[44px] text-[#17171C] max-w-[462px]">Загрузите приложение для
          своего устройства</h4>
        <h5 class="font-normal text-xl leading-[140%] text-[#2B2B30] mb-12">Приложение поддерживает системы iOS, Android.</h5>
        <div class="flex gap-5">
          <img src="@/assets/images/appstore.svg" alt="image">
          <img src="@/assets/images/palymarket.svg" alt="image">
        </div>
      </div>
    </div>


  <!--RIGHT SECTION WITH PHONE IMAGE -->

  <div>
    <InfoMockup/>
  </div>
  </div>
</template>

<script setup>
import InfoMockup from "@/components/InfoMockup.vue";
</script>