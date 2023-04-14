<script setup>
import HelloWorld from './components/HelloWorld.vue'

const ano = new Date().getFullYear()
</script>

<template>
  <HelloWorld />

  <div class="w-full h-16"></div>
  <footer class="fixed bottom-0 text-center w-full text-[#F8F8F2] bg-[#242424] p-4">
    © {{ ano }} Robinson Dev - Todos os direitos reservados
  </footer>
</template>
