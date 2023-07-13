<script>
export default {
    name: "FooterComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <footer class="footer-top">
        
    </footer>
    <footer class="footer-center">
        
    </footer>
    <footer class="footer-bottom">
        
    </footer>

</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

    footer {
        padding: $main-padding;
    }
    .footer-top {
        background-color: #0282f9;
    }
    .footer-center {
        background-image: url(../assets/img/footer-bg.jpg);
        height: 100%;
    }
    .footer-bottom {
        background-color: #303030;
    }
</style>