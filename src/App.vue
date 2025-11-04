<script setup lang="ts">
import Started from './components/started.vue'
</script>

<template>
  <div class="app">
    <div class="content">
      <Started/>
    </div>
  </div>
</template>

<style>
  .app{
    height: 100vh;
    color: #000;
  }
  .content{
    width: 1000px;
    min-height: 700px;
    background-color: #fff;
    margin: 0 auto;
    padding: 5rem 0;
  }
</style>
