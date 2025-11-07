<template>
  <div class="app font-monospaced">
    <div class="content">
      <div class="start">
        <Started/>
      </div>
      <div class="search-panel">
        <SearchPanel/>
        <AppFilter/>
      </div>
      <div class="movie">
        <MovieList/>
        <MovieAddForm/>
      </div>
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
    width: 800px;
    min-height: 800px;
    margin: 0 auto;
  }
  .start{
    margin-bottom: 2rem;
    text-align: start;
    padding: 1.8rem;
    margin-top: 70px;
    background-color: #f5eedf;
    border-radius: 8px;
    box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.55);
  }
  .search-panel{
    margin-top: 2rem;
    padding: 1.5rem;
    background-color: #f5eedf;
    border-radius: 4px;
    box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
  }
  .movie{

  }
</style>
