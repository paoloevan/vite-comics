<script>
import HeaderFooter from './HeaderFooter.vue'
import MainFooter from './MainFooter.vue'
import FooterFooter from './FooterFooter.vue'

export default {
    name: 'SiteFooter',
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

        <HeaderFooter />
        <MainFooter />
        <FooterFooter />





    </footer>
    <!-- / footer -->
</template>

<style lang="scss">

</style>