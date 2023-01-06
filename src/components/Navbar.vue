<template>
<div class=" p-2 my-2 mx-4 bg-white rounded-xl shadow-xl flex justify-between">
  <div class="flex cursor-pointer">
    <img src="../assets/images/logo-ipda.png" class=" h-12" alt="">
  </div>
  <div class="flex justify-center ">
    <ul class="flex justify-center items-center px-2 text-sm">
      <li class="px-4 py-2 flex w-full items-start hover:bg-gray-100 no-underline hover:no-underline transition-colors duration-100 cursor-pointer">Accueil</li>
      <li class="px-4 py-2 flex w-full items-start hover:bg-gray-100 no-underline hover:no-underline transition-colors duration-100 cursor-pointer">Contact</li>
      <li class="px-4 py-2 flex w-full items-start hover:bg-gray-100 no-underline hover:no-underline transition-colors duration-100 cursor-pointer" >About</li>
      
    </ul>
  </div>
  <div class="flex justify-center items-center">
    <router-link to="/login"><button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
 Connexion
</button></router-link>
  </div>
</div>
</template>



<script>
import { RouterLink } from 'vue-router';

</script>


<style>


</style>