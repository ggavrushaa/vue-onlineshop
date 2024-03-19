<template>
      <header class="flex justify-between border-b border-slate-200 px-10 py-8">
        <div class="flex items-center gap-4">
          <img src="/logo.jpg" alt="Logo" width="100px" height="100px" />
          <div>
            <h2 class="text-xl font-bold uppercase">Sneakers mall</h2>
            <p class="text-slate-500">The best Nikitin`s sneakers store</p>
          </div>
        </div>

        <ul class="flex items-center gap-10">

          <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
            <img src="/cart.svg" alt="Cart">
            <b>1205 $</b>
          </li>

          <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
            <img src="/heart.svg" alt="Heart">
            <span>Закладки</span>
          </li>

          <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
            <img src="/profile.svg" alt="Profile">
            <span>Профиль</span>
          </li>

        </ul>
    </header>
</template>