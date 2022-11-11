<script>
export default {
    name: 'ComicItem',
    props: {
        img: String,
        price: String,
        series: String,
        type: String,
    }
}
</script>

<template>
    <div class="my_card col_2">
        <div class="card_image">
            <img :src="img" :alt="series">
        </div>
        <div class=" card_title">
            {{ series }}
        </div>
    </div>
</template>