<script>
export default {
    name: "MainComponent",

    data() {

        return {

        }
    },
    props: {
    items: {
      type: Array,
      required: true,
        },
    },
    methods: {

    }
}
</script>

<template>
    <main>
        <div class="jumbo">
        </div>
        <div class="container">
            <div class="button">
                <a href="#">CURRENT SERIES</a>
            </div>
            <div class="row">
                <div class="col" v-for="item in items" :key="item.thumb">
                    <img :src="item.thumb" alt="Thumbnail" />
                    <p>{{ item.series }}</p>
                </div>
            </div>
        </div>
        <div class="button">
                <a href="#">LEARN MORE</a>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

main {
    background-color: black;
    .jumbo {
        background-image: url(../assets/img/jumbotron.jpg);
        height: 350px;
        background-size: cover;
    }
    .button:not(:first-child) {
        text-align: center;
         a {
            color: white;
            text-decoration: none;
            padding: 10px 25px;
            background-color: #0282f9;
            font-weight: 700;
            display: inline-block;
            margin-bottom: 15px;
            font-size: 10px;
      }
    }
    
};
.container {
    padding: 40px;
    background-color: black;
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
    .button a {
            color: white;
            text-decoration: none;
            padding: 10px;
            background-color: #0282f9;
            font-weight: 700;
            position: absolute;
            top: -20px;
    }
    .row {
        display: flex;
        flex-wrap: wrap;
        .col {
            width: calc(100% / 6 - 20px);
            margin: 0 10px;
            margin-bottom: 25px;
                img {
                    width: 100%;
                    height: 250px;
                    object-fit: cover;
                }
                p {
                    text-transform: uppercase;
                    font-size: 12px;
                }
        }
    }
}
</style>