<script setup>
    import DrawerHead from './DrawerHead.vue'
    import CartListItem from './CartListItem.vue'
    import Card from './Card.vue';
</script>

<template>
    <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
    
    <!-- Drawer start -->
  <div class="flex flex-col bg-white w-96 h-full fixed top-0 right-0 z-20 p-8">
       <DrawerHead />

      <CartListItem />
      <div class="flex flex-col gap-4 mt-7">
        <div class="flex gap-2">
            <span>Total:</span>
            <div class="flex-1 border-b border-dashed"></div>
            <b>1290$</b>
        </div>
        <div class="flex gap-2">
            <span>Fee 10%</span>
            <div class="flex-1 border-b border-dashed"></div>
            <b>129$</b>
        </div>
        <button
         disabled=""
         class="mt-4 flex justify-center items-center gap-3 w-full py-3 mt-10 bg-lime-500 text-white disabled:bg-slate-300 rounded-xl transition active:bg-lime-700 hover:bg-lime-600 cursor-pointer"
        >
         Оформить заказ
        <img src="/arrow-next.svg" alt="Arrow" />
        </button>
    </div>
  </div>
  <!-- Drawer end -->

</template>    