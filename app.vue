<script setup>
import Head from './components/Head.vue'
</script>

<template>
  <div>
    <header>
      <Head />
    </header>
    <div class="content">
      <NuxtPage></NuxtPage>
    </div>
  </div>
</template>

<style>
@import 'normalize.css';
@import url('./assets/css/base.css');
</style>
