<template>
  <div class="w-full h-screen grid grid-cols-1 grid-rows-6 font-poppins">
    <header class="row-span-2 flex items-stretch w-full">
      <h1 class=" self-end font-black text-5xl uppercase tracking-wider text-center mx-auto">Busque sua letra!</h1>
    </header>

    <form class="row-span-3 px-4 flex flex-col justify-center">
      <div>
        <input type="text" placeholder="Artista" id="artist" class="border-2 border-gray-200 rounded-md py-4 px-4 w-full focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent">
      </div>
      <div class="mt-6">
        <input type="text" id="song" placeholder="Nome da musica" class="border-2 border-gray-200 rounded-md py-4 px-4 w-full focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent">
      </div>
      <button type="submit" class="inline-flex justify-center py-4 px-4 border border-transparent shadow-sm text-md font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 w-full mx-auto mt-8">Buscar</button>
    </form>

    <footer class="row-span-1 text-center font-light">
      <span class="block">Todos direitos reservado.</span>
      <span>Desenvolvido por @vitordepaula1</span>
    </footer>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
