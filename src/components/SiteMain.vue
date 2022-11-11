<script>
import ComicList from './ComicList.vue'

export default {
    name: 'SiteMain',
    components: {
        ComicList
    }
}
</script>

<template>
    <main id="site_main">

        <div class="jumbotron">
            <img src="../assets/img/jumbotron.jpg" alt="">

            <span class="current">current series</span>

        </div>



        <ComicList />

    </main>
    <!-- / Main -->
</template>
