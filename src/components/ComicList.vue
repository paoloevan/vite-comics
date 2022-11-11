<script>
import comics from '../../vue-dc-comics-2/dc-comics';
import ComicItem from './ComicItem.vue'

export default {
    name: 'ComicList',
    components: {
        comics,
        ComicItem
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
        <ComicItem v-for="card in comics" :img="card.thumb" :price="card.price" :series="card.series"
            :type="card.type" />
    </div>
</template>
