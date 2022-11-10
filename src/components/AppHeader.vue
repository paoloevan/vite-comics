<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="container">

        <img src="../assets/img/dc-logo.png" alt="">

        <div class="navbar">
            <a href="#">characters</a>
            <a href="#">comics</a>
            <a href="#">movies</a>
            <a href="#">tv</a>
            <a href="#">games</a>
            <a href="#">collectibles</a>
            <a href="#">videos</a>
            <a href="#">fans</a>
            <a href="#">news</a>
            <a href="#">shop</a>
        </div>
    </div>
</template>

<style>
.container {
    max-width: 1200px;
    margin: auto;
}

.navbar {
    display: inline-block;
}

.navbar a {
    padding: 1rem;
}
</style>