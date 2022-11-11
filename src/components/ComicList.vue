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

<style lang="scss" scoped>
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 3rem 0;

    .my_card {

        .card_image {
            width: 200px;
            aspect-ratio: 1;
            padding: 0.5rem;


            img {
                width: 100%;
                height: 100%;
                object-fit: cover;
            }
        }

        .card_title {
            color: white;
            text-transform: uppercase;
            font-size: 0.75rem;
            padding: 0.5rem;

        }
    }
}
</style>