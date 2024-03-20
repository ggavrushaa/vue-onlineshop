<script setup>
  import Header from './components/Header.vue';
  import CardList from './components/CardList.vue';
  import Drawer from './components/Drawer.vue';
</script>

<template>
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-14">
    <Header />
 
    <div class="p-10">
      <!-- <Drawer /> -->
  <div class="flex justify-between items-center">

      <h2 class="text-3xl font-bold mb-8">All sneakers</h2>

<div class="flex gap-4">
  <select class="py-2 px-3 border rounded-md outline-none">
      <option>By title</option>
      <option>By price(cheap)</option>
      <option>By price(expensive)</option>
    </select>

      <div class="relative">
        <img 
        class="absolute left-3 top-3"
        src="/search.svg"
         alt="Search"
         />
        <input
          class="border rounded-md py-2 pl-10 pr-4 outline-none focus:border-gray-300"
          type="text" 
          placeholder="Search"
         />
    </div>  
</div>

  </div>

      <CardList />
    </div>
  </div>
</template>

<style scoped>

</style>
