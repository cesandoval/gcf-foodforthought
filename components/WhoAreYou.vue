<script setup></script>

<template>
  <div class="grid grid-cols-1 place-items-center px-5">
    <div class="rounded-3xl bg-lime-300 px-10 py-8">
      <h1 class="uppercase text-center mb-4">💡 Did you know?</h1>
      <p class="text-sm mb-2">
        Within the past 10 years, Green City Force has:
      </p>
      <ul class="text-sm list-disc">
        <li>had 20 cohorts 💪</li>
        <li>500 graduates 🎓</li>
        <li>reached 50,000+ public housing residents 🏘️</li>
        <li>built 6 farms across NYCHA developments 🧑‍🌾</li>
        <li>distributed 150,000 lbs of organic produce 🥦</li>
      </ul>
    </div>
  </div>

  <SeparatorLine />

  <div class="grid grid-cols-1 place-items-center">
    <img class="-mt-12 px-10" src="/imgs/section-01.png" />
    <p class="px-16 text-center">
      Why don’t you tell us a bit about yourself, so that we can give you more
      relevant information.<br />🤝
    </p>
  </div>

  <SeparatorLine />

  <OptionButton
    :question="'Who are you?'"
    :options="['Resident 🏡', 'Volunteer 🙋', 'Supporter 💪']"
  />
</template>

<style scoped></style>
