<script setup lang="ts">
import Login from "./components/login.vue"



</script>

<template>
  <div class="max-w-screen  h-screen flex justify-between " > 
    <div class="grid grid-cols-5 w-full md:w-1/2">

      <div class="col-span-5  lg:col-start-2 lg:col-span-3 w-full">
        <div class="h-full w-full grid grid-row-8 p-10 gap-12 justify-items-center ">
     <div class="row-span-1 w-full "><div><img src="./assets/Header.svg" class=" w-42 " alt=""></div> </div> 
     <div class="row-span-6 w-full "><Login/> </div>

    </div>  
      </div>
      <div class="col-start-1 col-span-3">      <div class=" flex p-5 w-full items-center mt-20 text-gray-500 row-span-1">
        <p class="font-bold text-sm  ">  &copy;  </p> <p class="font-light text-xs ">Excite! innovation company 2077</p>
      </div></div>
    </div>

    

<!-- <img src="./assets/side2.svg"class="w-1/2" alt="" srcset=""> -->
  <div class="hidden  lg:flex lg:w-1/2 bg-no-repeat bg-right bg-[url('./assets/side15.svg')] bg-contain "></div>

  </div>

</template>

<style scoped>

</style>
