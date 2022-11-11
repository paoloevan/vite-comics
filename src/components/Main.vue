<script>
import ComicList from '../components/ComicList.vue'

export default {
    name: 'Main',
    components: {
        ComicList
    }
}
</script>

<template>
    <main id="site_main">

        <div class="jumbotron">
            <img src="../assets/img/jumbotron.jpg" alt="">

        </div>

        <ComicList />

    </main>
    <!-- / Main -->
</template>

<style lang="scss">
.jumbotron {
    height: 300px;
    width: 100%;

    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
    }
}
</style>