<template>
  <div class="relative">
    <div class="mockup w-[503px] h-[632px] ">
      <img src="@/assets/images/mockup.png" alt="image">
    </div>
    <!--1 card-->
    <div class="flex absolute top-[59px] left-2.5">
      <img src="@/assets/images/car1.svg" alt="">

      <div class="absolute left-11 bg-[#F53B57] rounded-3xl p-2 flex items-center gap-2 w-max ">
        <div class="check px-1.5 py-2 bg-white w-6 rounded-3xl">
          <img src="@/assets/images/check.svg" alt="#">
        </div>
        <h4 class="font-'averta-CY' font-semibold text-[10px] leading-[120%] text-white max-w-[102px]">
          Возможность брать машину в аренду
        </h4>
      </div>
    </div>
<!--2ccard-->

    <div class="flex absolute -left-[225px] top-[20%]">
      <img src="@/assets/images/car2.svg" alt="">

      <div class="absolute left-[52px] bg-[#05C46B] rounded-3xl p-2 flex items-center gap-2 w-max ">
        <div class="check1 px-1.5 py-2 bg-white w-6 rounded-3xl">
          <img src="@/assets/images/check.svg" alt="#">
        </div>
        <h4 class="font-'averta-CY' font-semibold text-[10px] leading-[120%] text-white max-w-[100px]">
          Легкая  продажа авто
        </h4>
      </div>
    </div>


    <!--3 card-->

    <div class="flex bottom-[113px] -left-[177px] absolute">
      <img src="@/assets/images/car3.svg" alt="">
      <div class="absolute left-[52px] bg-[#FFA801] rounded-3xl p-2 flex items-center gap-2 w-max ">
        <div class="check2 px-1.5 py-2 bg-white w-6 rounded-3xl">
          <img src="@/assets/images/check.svg" alt="#">
        </div>
        <h4 class="font-'averta-CY' font-semibold text-[10px] leading-[120%] text-white max-w-[96px]">
          Легкая покупка авто
        </h4>
      </div>
    </div>



  </div>

</template>


<style>
  .check {
    box-shadow: 0px 3px 10px #A8293C;
  }
  .check1{
    box-shadow: 0px 3px 10px #006838;
  }
  .check {
    box-shadow: 0px 3px 6px #BF7E01;
  }
  @media (min-width: ) {
    
  }
</style>