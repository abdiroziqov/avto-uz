<template>
  <div class="card mt-[72px] gap-6 grid lg:grid-cols-4 sm:grid-cols-2">
    <div v-for="(item, idx) in cards" :key="idx"
        :style="{ 'background': item.cardBackground }"
        class=" flex items-center pt-8 pl-4 pb-1.5  border border-[rgba(23,23,37,0.1)] rounded-2xl shadow-[0px20px32pxrgba(0,0,0,0.02)] bg-[#FFF8EF] justify-between">
      <div>
        <h3 :style="{ 'color': item.titleColor }"
            class="font-family: 'Averta CY' font-bold leading-[130%] text-[#663B06] max-w-[185px]">
          {{item.title}}
        </h3>
        <h4 :style="{ 'color': item.textColor }"
            class="font-family: 'Averta CY' font-normal text-xs leading-[130%] text-[#C8904D]">
          {{item.subtitle}}
        </h4>
      </div>
      <div>
        <img :src="item.img" alt="image" />
      </div>
    </div>
  </div>
</template>


<script setup>
  import {ref} from "vue";

  const cards = [
    {
      cardBackground:'#FFF8EF',
      textColor: '#C8904D',
      titleColor:'#663B06',
      title: 'Сервисы',
      subtitle: 'Проверенные сервисы auto.uz',
      img: "/src/assets/images/card1.svg",

      },
    {
      cardBackground:'#F1EFFF',
      textColor: '#9F4DC8',
      titleColor:'#460666',
      title: 'Проверенные автомобили',
      subtitle: 'Объявления от avto.uz',
      img: "/src/assets/images/card2.svg",
    },
    {
      cardBackground:'#DAECFF',
      textColor: '#4D88C8',
      titleColor:'#063466',
      title: 'Профессиональная объявление',
      subtitle: 'Объявления от avto.uz',
      img: "/src/assets/images/card3.svg",
    },
    {
      cardBackground:'#FFF0EF',
      textColor: '#C8534D',
      titleColor:'#660A06',
      title: 'Каршеринг',
      subtitle: 'Каршеринг в auto.uz',
      img: "/src/assets/images/card4.svg",
    },


    {
      cardBackground:'#DAECFF',
      textColor: '#4D88C8',
      titleColor:'#063466',
      title: 'Профессиональная объявление',
      subtitle: 'Объявления от avto.uz',
      img: "/src/assets/images/card3.svg",
    },
    {
      cardBackground:'#FFF0EF',
      textColor: '#C8534D',
      titleColor:'#660A06',
      title: 'Каршеринг',
      subtitle: 'Каршеринг в auto.uz',
      img: "/src/assets/images/card4.svg",
    },
    {
      cardBackground:'#FFF8EF',
      textColor: '#C8904D',
      titleColor:'#663B06',
      title: 'Сервисы',
      subtitle: 'Проверенные сервисы auto.uz',
      img: "/src/assets/images/card1.svg",

    },
    {
      cardBackground:'#F1EFFF',
      textColor: '#9F4DC8',
      titleColor:'#460666',
      title: 'Проверенные автомобили',
      subtitle: 'Объявления от avto.uz',
      img: "/src/assets/images/card2.svg",
    },
  ];


</script>

<style scoped>
  .card{
    display: grid;
    //grid-template-columns: repeat(4, minmax(0, 2fr));
  }
</style>