<template>
  <div>
    <div>
  <router-view />
</div>
<div>
<contentPage/>
</div>
</div>
</template>

<script setup lang="ts">
import contentPage from './layouts/contentPage.vue';
</script>
