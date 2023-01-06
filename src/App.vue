<script setup>
import { RouterView } from 'vue-router';
import Navbar from '@/components/Navbar.vue'
import Sidebar from '@/components/Sidebar.vue'

</script>

<template>
  <main class="bg-blue-400 border h-screen ">
    <Navbar />
    <div class="flex">
    <Sidebar />
    <div class="bg-white flex-1 p-4 mr-2 overscroll-y-contain rounded-2xl shadow-xl">

    <RouterView />
    </div>
  </div>
  </main>
 
</template>

<style scoped>


</style>
