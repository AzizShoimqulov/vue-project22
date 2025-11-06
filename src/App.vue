<template>
  <div class="app">
    <div class="content">
      <Started/>
      <div class="search-panel">
        <SearchPanel/>
        <AppFilter/>
      </div>
      <MovieList/>
      <MovieAddForm/>
    </div>
  </div>
</template>


<script setup lang="ts">
import AppFilter from './components/app-filter.vue';
import MovieAddForm from './components/movie-list/MovieAddForm.vue';
import MovieList from './components/movie-list/MovieList.vue';
import SearchPanel from './components/Search-panel.vue';
import Started from './components/started.vue';

</script>


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
