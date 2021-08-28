<template>
  <div>

    <div class="min-h-screen bg-gray-700 flex items-center justify-center">
      
      <!-- calculator goes here -->
      <div class="bg-gray-100 border-2 border-gray-900 shadow-2xl rounded-lg">
       
        <!-- form goes here --> 
        <form class="bg-gray-400 border-b-2 border-gray-900">
          <input type="number" class="bg-transparent p-8 rounded-t-lg outline-none focus:bg-gray-700 text-3xl text-right text-white font-mono">
        </form>

        <!-- buttons go here -->
        <div class="p-6 text-gray-800 grid grid-cols-4 gap-4 text-xl">
          <button class="font-mono col-span-3 bg-yellow-400 hover:bg-yellow-300 border-b-2 border-gray-900 rounded-xl p-5">C</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">&divide;</button>

          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">1</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">2</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">3</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">&times;</button>

          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">4</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">5</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">6</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">&minus;</button>

          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">7</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">8</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">9</button>
          <button class="font-mono bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900 -400 rounded-xl p-5">&plus;</button>

          <button class="font-mono bg-gray-300 hover:bg-gray-200 border-b-2 border-gray-900  rounded-xl p-5">0</button>
          <button class="font-mono col-span-3 bg-gray-500 hover:bg-gray-400 border-b-2 border-gray-900  rounded-xl p-5">&equals;</button>
        </div>
      </div>

    </div>
  </div>
</template>

<script setup>

</script>

<style>

</style>
