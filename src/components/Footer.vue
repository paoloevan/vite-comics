<script>
export default {
    name: 'Footer',
    data() {
        return {
            buy: [
                {
                    text: 'digital comics',
                    image: '../assets/img/buy-comics-digital-comics.png'
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

            ],
            links: [
                {
                    title: 'dc comics',
                    link: [
                        {
                            href: '#',
                            text: 'Characters'
                        },
                        {
                            href: '#',
                            text: 'Comics'
                        },
                        {
                            href: '#',
                            text: 'Movies'
                        },
                        {
                            href: '#',
                            text: 'Tv'
                        },
                        {
                            href: '#',
                            text: 'Games'
                        },
                        {
                            href: '#',
                            text: 'Videos'
                        },
                        {
                            href: '#',
                            text: 'News'
                        }

                    ]
                },
                {
                    title: 'shop',
                    link: [
                        {
                            href: '#',
                            text: 'Shop Dc'
                        },
                        {
                            href: '#',
                            text: 'Shop Dc Collectibles'
                        },
                    ]
                }
            ],
            linksTwo: [
                {
                    title: 'dc',
                    link: [
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },

                    ]
                }
            ],
            sities: [
                {
                    title: 'sities',
                    link: [
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        },
                        {
                            href: '#',
                            text: 'lorem lorem'
                        }
                    ]
                }

            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL(name, import.meta.url).href
        }

    }
}
</script>

<template>
    <footer id="site_footer">

        <div class="header_footer">
            <div v-for="img in buy" class="buy">
                <img :src="getImageUrl(img.image)" alt="">
                {{ img.text }}
            </div>
        </div>

        <div class="main_footer">
            <div class="container">
                <div class="content">
                    <div class="col_4">
                        <div v-for="link in links">
                            <div class="footer_title">{{ link.title }}</div>
                            <a class="footer_link" v-for="text in link.link" :href="text.href">{{ text.text }}</a>
                        </div>
                    </div>
                    <div class="col_4">
                        <div v-for="link in linksTwo">
                            <div class="footer_title">{{ link.title }}</div>
                            <a class="footer_link" v-for="text in link.link" :href="text.href">{{ text.text }}</a>
                        </div>
                    </div>
                    <div class="col_4">
                        <div v-for="link in sities">
                            <div class="footer_title">{{ link.title }}</div>
                            <a class="footer_link" v-for="text in link.link" :href="text.href">{{ text.text }}</a>
                        </div>
                    </div>

                </div>

                <div class="logo_bg">

                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>

        <div class="footer_footer">
            .<div class="container">
                <button>sign-up now</button>

                <div class="social">
                    <span>follow us</span>
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-youtube"></i>
                    <i class="fa-brands fa-pinterest-p"></i>
                    <i class="fa-solid fa-location-dot"></i>
                </div>
            </div>



        </div>
    </footer>
    <!-- / footer -->
</template>

<style lang="scss">

</style>