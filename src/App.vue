<template>
  <Navbar></Navbar>
  <LandingPage></LandingPage>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Navbar from './components/Navbar.vue'
import LandingPage from './components/LandingPage.vue'

export default defineComponent({
  name: 'App',
  components: {
    Navbar, LandingPage
  }
})
</script>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
