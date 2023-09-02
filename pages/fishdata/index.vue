<script setup>
  const data = [
    {
        "id": 1,
        "name": "メバル",
        "place": "北海道南部～九州の沿岸部",
        "season": "春から冬"
    },
    {
        "id": 2,
        "name": "アジ",
        "place": "全国各地",
        "season": "初夏から晩夏"
    },
    {
        "id": 3,
        "name": "カサゴ",
        "place": "日本近海～太平洋西部",
        "season": "冬から春"
    },
    {
        "id": 4,
        "name": "キジハタ",
        "place": "日本から中国沿岸",
        "season": "春から夏"
    },
    {
        "id": 5,
        "name": "スズキ",
        "place": "北海道南部～九州の沿岸部",
        "season": "春から夏"
    },
    {
        "id": 6,
        "name": "ブリ",
        "place": "北海道～九州の太平洋岸",
        "season": "冬"
    }
  ]
</script>
<template>
  <div class="pt-3">

    <h1 class="text-2xl pb-6 text-red-700">Fish data</h1>
    <div v-for="value in data">
      <NuxtLink class="underline underline-offset-2" to="/">{{ value.name }}</NuxtLink>
    </div>
  </div>
</template>