<script>
import comics from '../../vue-dc-comics-2/dc-comics';
import Comic from '../components/Comic.vue'

export default {
    name: 'ComicList',
    components: {
        comics,
        Comic
    },
    data() {
        return {
            comics: comics
        }
    }
}
</script>

<template>
    .<div class="container">
        <Comic v-for="card in comics" :img="card.thumb" :price="card.price" :series="card.series" :type="card.type" />



    </div>
</template>
