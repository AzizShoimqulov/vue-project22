<template>
    <div class="movie-form">
        <h1>Yangi kino qushish</h1>
        <div class="movie-add">
        </div>
        <input type="text" placeholder="Qanday kino?">
        <input type="text" placeholder="Nechi marotaba ko'rilgan?">
        <button>Qo'shish</button>
    </div>
</template>


<script>
export default {}
</script>


<style scoped>    
    .movie-form{
        margin-top: 2rem;
        padding: 1.5rem;
        background-color: #f5eedf;
        border-radius: 4px;
        box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
    }
    .movie-add{
        display: flex;
        gap: 1rem;
    }
    .movie-form input{
        width: 320px;
        padding: 0.5rem;
        border: 1px solid rgb(116, 110, 110);
        border-radius: 4px;
    }
    .movie-form button{
        padding: 0.5rem;
        border: 1px solid rgb(116, 110, 110);
        background-color: #ffffff;
        color: #0d0d0d;
        border-radius: 4px;
        cursor: pointer;
    }
</style>