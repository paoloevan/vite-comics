<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            navbar: [
                {
                    text: `characters`,
                    href: '#'

                },
                {
                    text: `comics`,
                    href: '#'

                },
                {
                    text: `movies`,
                    href: '#'

                },
                {
                    text: `tv`,
                    href: '#'

                },
                {
                    text: `games`,
                    href: '#'

                },
                {
                    text: `videos`,
                    href: '#'

                },
                {
                    text: `fans`,
                    href: '#'

                },
                {
                    text: `news`,
                    href: '#'

                },
                {
                    text: `shop`,
                    href: '#'

                },
            ]
        }
    }
}

</script>

<template>
    <header>

        <div class="container">

            <img src="../assets/img/dc-logo.png" alt="">

            <div class="navbar">
                <a v-for="link in navbar" :href="link.href">{{ link.text }}</a>
            </div>
        </div>
    </header>
</template>

<style lang="scss">

</style>