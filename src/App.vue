<template>
  <Navbar></Navbar>

  <div class="bg-gray-50 px-40">
    <div class="flex h-screen">
      <div class="flex items-center justify-end w-full pr-14">
        <div class="relative h-auto w-auto">
          <img src="./assets/celine-portrait.png" alt="celine-portrait" class="relative h-full w-full max-h-80 max-w-xs rounded-full border-2 border-green-600 z-10 filter drop-shadow-lg">
          <div class="absolute top-1/2 right-1/2 z-0 bg-green-400 h-3/5 w-3/5 rounded-full bg-gradient-to-tr from-green-600 to-green-200"></div>
          <div class="absolute bottom-1/3 left-1/3 z-0 h-4/5 w-4/5 rounded-full bg-gradient-to-tr from-green-600 to-green-200"></div>
        </div>
      </div>
      <div class="flex flex-col justify-center pl-20">
        <h1 class="text-6xl font-semibold tracking-wide text-green-600 pb-2">Hi, I'm Celine</h1>
        <h2 class="text-4xl text-green-400 pb-2">Experienced Product Manager</h2>
        <h3 class="text-2xl pb-2">Product Manager / Brand Manager / Marketer</h3>
        <p>
          Content marketing is an approach that helps your brand build long-term relationships with a user and gain
          his trust. I know everything about content marketing and its techniques, and I will be happy to help you
          promote your project.
        </p>
      </div>
    </div>

    <div class="h-screen">

    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Navbar from './components/Navbar.vue'

export default defineComponent({
  name: 'App',
  components: {
    Navbar
  }
})
</script>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
