<script>
export default {
    name: MainFooter
}
</script>

<template>
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

</template>