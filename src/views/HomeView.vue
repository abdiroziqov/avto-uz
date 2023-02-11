

<template>
 <section class="main w-full h-full bg-[#e5e5e5]">
   <main class="pt-6">
     <div class="container ">
       <LogoSide />
       <InfoSection/>
        <InfoCards/>
       <Footer/>
     </div>
   </main>
 </section>
</template>

<script setup>
import LogoSide from "@/components/LogoSide.vue";
import InfoSection from "@/components/InfoSection.vue";
import InfoCards from "@/components/InfoCards.vue";
import Footer from "@/components/Footer.vue"
</script>


<style scoped>

</style>

