<script setup>
  import data from "/data.json"
  const route = useRoute()
  const id = Number(route.params.id)
  const fishdata = data.find(res=>res.id === id)
</script>
<template>
  <div>
    <!-- 詳細ページ -->
    <div class="my-4 p-4 bg-red-100">
      <!-- 名称 -->
      <div class="p-1 flex">
        <div class="pr-4">
          名称
        </div>
        <div class="text-fuchsia-900 text-xl font-bold">
          {{ fishdata.name }}
        </div>
      </div>
      <!-- 生息地 -->
      <div class="p-1 flex">
        <div class="pr-4">
          生息地
        </div>
        <div class="text-fuchsia-900 text-xl font-bold">
          {{ fishdata.place }}
        </div>
      </div>
      <!-- 旬 -->
      <div class="p-1 flex">
        <div class="pr-4">
          旬
        </div>
        <div class="text-fuchsia-900 text-xl font-bold">
          {{ fishdata.season }}
        </div>
      </div>
    </div>
    <NuxtLink to="/fishdata">戻る</NuxtLink>
  </div>
</template>