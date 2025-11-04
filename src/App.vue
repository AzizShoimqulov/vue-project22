<script setup lang="ts">
import SearchPanel from './components/Search-panel.vue';
import Started from './components/started.vue'
</script>

<template>
  <div class="app">
    <div class="content">
      <Started/>
      <div class="search-panel">
        <SearchPanel/>
      </div>
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
  .search-panel{
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #f5eedf;
    border-radius: 4px;
    box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
  }
</style>
