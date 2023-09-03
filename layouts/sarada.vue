<template>
  <div class="bg-slate-50 p-12">
    <slot />
  </div>
</template>

<script setup lang="ts">
// ヘッダーメタ情報を設定
  useHead({
    title: 'サラダ・ミーティング',
    meta: [
      { name: 'description', content: '新鮮なつながりを、ひとつのサラダから'}
    ]
  })
</script>