<template>
  <div class="bg-slate-50 p-12">
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

// ヘッダーメタ情報を設定【useSeoMataを使った場合】
/*
useSeoMeta{{
  title: 'サラダ・ミーティング２',
  ogTitle: 'サラダ・ミーティング２',
  Description: '新鮮なつながりを、ひとつのサラダから',
  ogDescription: '新鮮なつながりを、ひとつのサラダから',
  ogImage: '',
  twitterCard: '',
}}

*/
</script>