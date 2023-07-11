<script setup>
import { useLocationStore } from '~/store/location'
const locationStore = useLocationStore()
const { changeCurrentLocation } = locationStore

changeCurrentLocation('landing')
</script>

<template>
  <div class="grid grid-cols-1 place-items-center px-1 pt-10">
    <div class="py-3 text-center">
      <p>Nice to meet you 👋</p>
    </div>
    <div>
      <p class="py-2 text-center uppercase">WE ARE</p>
      <p class="uppercase border-2 border-black rounded-full px-3 mb-12">
        Green City Force
      </p>
    </div>
  </div>
  <img src="imgs/landing.png" alt="" />
  <SeparatorLine />
</template>

<style scoped></style>
