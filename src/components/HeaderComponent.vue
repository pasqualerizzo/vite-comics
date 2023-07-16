<script>
export default {
    name: "HeaderComponent",
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li>
                <a href="#">
                    CHARACTERS
                </a>
            </li>
            <li>
                <a class="active" href="#">
                    COMICS
                </a>
            </li>
            <li>
                <a href="#">
                    MOVIES
                </a>
            </li>
            <li>
                <a href="#">
                    TV
                </a>
            </li>
            <li>
                <a href="#">
                    GAMES
                </a>
            </li>
            <li>
                <a href="#">
                    COLLECTIBLES
                </a>
            </li>
            <li>
                <a href="#">
                    VIDEOS
                </a>
            </li>
            <li>
                <a href="#">
                    FANS
                </a>
            </li>
            <li>
                <a href="#">
                    NEWS
                </a>
            </li>
            <li>
                <a href="#">
                    SHOP
                </a>
            </li>
        </ul>

        </div>
        
    </header>
</template>

<style lang="scss" scoped>

    header {
        background-color: #ffff;
    }
    .container {
        padding: 20px;
        background-color: #ffff;
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1200px;
        margin:auto
    }
    header img {
        height: 75px;
    }
    header ul {
        display: inline;
    }
    header ul li {
        display: inline;
        margin-left: 15px;
    }
    header a {
        text-decoration: none;
        color: black;
        font-size: 12px;
    };
    header a:hover {
        color: blue;
        font-weight: 600;
    }
    .active {
        color: blue;
    }
</style>