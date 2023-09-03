<script>
definePageMeta({
  layout: "custom",
});// This will work in both `<script setup>` and `<script>`

</script>
<template>
  <div class="pt-3">
    <h1 class="text-2xl pb-6 text-red-700">SecondPageですよ</h1>
    <NuxtLink class="underline underline-offset-2" to="/">Goto Home</NuxtLink>
    <p class="text-green-800 py-3">📌 このページ専用にカスタマイズしたレイアウトを使っています。</p>
  </div>
</template>
