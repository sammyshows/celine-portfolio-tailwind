<template>
  <div class="bg-gray-50 px-40 pt-12">
    <div class="flex h-screen">
      <div class="flex items-center justify-end w-full pr-14">
        <div class="relative h-auto w-auto">
          <img src="../assets/celine-portrait.jpg" alt="celine-portrait" class="relative h-full w-full max-w-md rounded-md z-10 filter drop-shadow-lg">
          <div class="stripes-grey absolute -bottom-6 -left-6 h-2/5 w-2/5 "></div>
          <div class="stripes-green absolute -top-6 -right-6 h-3/5 w-3/5"></div>
        </div>
      </div>
      <div class="flex flex-col justify-center pl-20 max-w-2xl">
        <h1 class="text-6xl font-extrabold tracking-wide text-celine-green pb-2">Hi, I'm Celine</h1>
        <h2 class="text-6xl font-extrabold text-green-700 pb-4">Experienced Product Manager</h2>
        <p class="text-xl leading-8">
          I'm a Melbourne based product and brand manager focused on building strong brand ands creating new products……
          lorem ipsum odor lorem ipsum odor lorem ipsum odorlorem ipsum odorlorem ipsum odorlorem ipsum odorlorem ipsum odor
          lorem ipsum odor
        </p>
      </div>
    </div>

    <div class="h-screen">

    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'LandingPage',
})
</script>

<style>
.stripes-green {
  background-image: linear-gradient(135deg, #69D873 25%, transparent 25%, transparent 50%, #69D873 50%, #69D873 75%, transparent 75%, #FFF);
  background-size: 10px 10px;
}

.stripes-grey {
  background-image: linear-gradient(135deg, #C2C2C2 25%, transparent 25%, transparent 50%, #C2C2C2 50%, #C2C2C2 75%, transparent 75%, #FFF);
  background-size: 10px 10px;
}
</style>