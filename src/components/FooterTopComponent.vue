<script>
export default {
    name: "FooterTopComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <div class="container">
        <div class="col">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
        </div>
        <div class="col">
            <img src="../assets/img/buy-comics-merchandise.png" alt="">

            <span>DC MERCHANDISE</span>
        </div>
        <div class="col">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">

            <span>SUBSCRIPTION</span>
        </div>
        <div class="col">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">

            <span>COMIC SHOP LOCATOR</span>
        </div>
        <div class="col">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;
    .container{
        max-width: 1200px;
        padding: 50px;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        .col {
            display: flex;
            align-items: center;
        }
        img {
            height: 50px;
        }
            span {
                display: inline-block;
                margin-left: 10px;
                color: white;
                font-size: 12px;
            }
    };

</style>