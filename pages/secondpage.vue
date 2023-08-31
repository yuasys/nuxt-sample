<script>
// This will work in both `<script setup>` and `<script>`
definePageMeta({
  layout: "custom",
});
</script>
<template>
  <div class="pt-3">
    <h1 class="text-2xl pb-6 text-red-700">SecondPageですよ</h1>
    <NuxtLink class="underline underline-offset-2" to="/">Goto Home</NuxtLink>
    <p class="text-red-600 py-3">※このページは独自にカスタマイズしたレイアウトを使っています。</p>
  </div>
</template>
