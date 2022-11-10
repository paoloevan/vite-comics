<script>
export default {
    name: 'Footer'
}
</script>

<template>
    <footer id="site_footer">
        <div class="header_footer"></div>
        <div class="main_footer"></div>
        <div class="footer_footer"></div>
    </footer>
    <!-- / footer -->
</template>

<style lang="scss">
.header_footer {
    background-color: blue;
    height: 220px;
}

.main_footer {
    height: 300px;
    background-image: url(../assets/img/footer-bg.jpg);
}

.footer_footer {
    background-color: gray;
    height: 100px;
}
</style>