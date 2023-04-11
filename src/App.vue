<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="estm.jpeg">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Aisyah Ahmad</div>
      <br>
      <div class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">21FTT1755</div>
      <br>
      <p class="mt-2 text-slate-500">Greetings, I am a student from Polytechnic Brunei taking Level 5 Diploma in Web Development.</p>
      <br>
      <p>🙂</p>
    </div>
  </div>
</div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
