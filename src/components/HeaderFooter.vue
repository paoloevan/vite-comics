<script>
export default {
    name: HeaderFooter
}
</script>

<template>
    <div class="header_footer">
        <div v-for="img in buy" class="buy">
            <img :src="getImageUrl(img.image)" alt="">
            {{ img.text }}
        </div>
    </div>
</template>