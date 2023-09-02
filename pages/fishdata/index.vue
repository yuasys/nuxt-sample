<script setup>
  import data from "/data.json"
</script>
<template>
  <div class="pt-3">

    <h1 class="text-2xl pb-6 text-red-700">Fish data</h1>
    <div v-for="value in data">
      <NuxtLink class="underline underline-offset-2" :to='"/fishdata/"+value.id'>{{ value.name }}</NuxtLink>
    </div>
  </div>
</template>