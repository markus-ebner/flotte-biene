<template>
  <div class="p-4 bg-[#FDCE29] text-[#7A5903] min-h-screen min-w-screen flex items-center justify-center flex-col gap-4 sm:gap-10">
    <div class="flex">
      <img class="rotate-90 w-20" src="public/biene.svg" alt="Flotte Biene Logo">
      <div >
        <h1 class="text-4xl sm:text-6xl font-extrabold">Flotte Biene</h1>
        <p class="block sm:text-xl">Webshop für Natur-, Textil- & Bienenprodukte</p>
      </div>
    </div>
    <div class="flex gap-4 flex-wrap justify-center">
      <img class="w-full sm:w-60 sm:h-60 object-cover rounded-2xl border border-[#7A5903] border-8" src="public/honig.jpeg" alt="Bienenhonig">
      <img class="w-full sm:w-60 sm:h-60 object-cover rounded-2xl border border-[#7A5903] border-8" src="public/ernte.jpg" alt="Scrunchies">
      <img class="w-full sm:w-60 sm:h-60 object-cover rounded-2xl border border-[#7A5903] border-8" src="public/bienenbeuten.jpg" alt="Cremen">
    </div>
  </div>
</template>
<script setup lang="ts">
useHead({
  meta: [
    { name: 'Flotte Biene Shop', content:  'Webshop für Natur-, Textil- & Bienenprodukte'}
  ],
})
</script>
