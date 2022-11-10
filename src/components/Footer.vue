<script>
export default {
    name: 'Footer',
    data() {
        return {
            buy: [
                {
                    text: 'digital comics',
                    image: 'buy-comics-digital-comics.png'
                },
                {
                    text: 'dc merchandise',
                    image: '../assets/img/buy-comics-merchandise.png'
                },
                {
                    text: 'subscription',
                    image: '../assets/img/buy-comics-shop-locator.png'
                },
                {
                    text: 'comic shop locator',
                    image: '../assets/img/buy-comics-subscriptions.png'
                },
                {
                    text: 'dc power visa',
                    image: '../assets/img/buy-dc-power-visa.svg'
                },

            ]
        }
    }
}
</script>

<template>
    <footer id="site_footer">
        <div class="header_footer">
            <div v-for="img in buy">
                <img :src="img.image" alt="">
                {{ img.text }}
            </div>
        </div>
        <div class="main_footer"></div>
        <div class="footer_footer"></div>
    </footer>
    <!-- / footer -->
</template>

<style lang="scss">

</style>