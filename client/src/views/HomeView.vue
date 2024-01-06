<template>
  <main>
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-4 bg-blue p-8 relative">
      <div class="col-span-3 flex flex-col justify-center">
        <h1 class="text-7xl font-semibold mb-2">Panda<span class="text-purple-700 hover:text-purple-900 transition">Media</span></h1>
        <p class="text-[#313131] ">Where Social Connections are as Playful as Pandas 🐼</p>
      </div>
      <div class="col-span-1 relative overflow-hidden">
        <img class="w-full h-auto rounded animate-slide-in" src="../assets/pandawelcome.png" alt="Panda Image">
        <div class="absolute top-0 left-0 w-full h-full flex items-center justify-center ">
          <h2 class="text-purple-700 text-3xl font-bold">Welcome</h2>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
@keyframes fade-in {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

@keyframes slide-in {
  0% { transform: translateX(100%); }
  100% { transform: translateX(0); }
}

.animate-fade-in {
  animation: fade-in 1s ease-out;
}

.animate-slide-in {
  animation: slide-in 1s ease-out;
}
</style>
