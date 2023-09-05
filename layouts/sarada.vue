<template>
  <div class="container w-11/12 max-w-6xl mx-auto bg-green-50">
    <slot />
  </div>
</template>

<script setup lang="ts">
// ヘッダーメタ情報を設定 【useHeadを使った場合】
  useHead({
    title: 'サラダ・ミーティング',
    meta: [
      { name: 'description', content: '新鮮なつながりを、ひとつのサラダから'}
    ]
  })
</script>
