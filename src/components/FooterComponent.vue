<script>
import FooterTopComponent from "../components/FooterTopComponent.vue";

export default {
    name: "FooterComponent",
    components: {
    FooterTopComponent ,
    },
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
        <FooterTopComponent/>
    </footer>
    <footer class="footer-center">
        <div class="container">
            <div class="col-1">
                <div>   
                    <h3>DC COMICS</h3>
                    <ul>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Movies</a>
                        </li>
                        <li>
                            <a href="#">Tv</a>
                        </li>
                        <li>
                            <a href="#">Games</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li>
                            <a href="#">Shop DC</a>
                        </li>
                        <li>
                            <a href="#">Shop DC Collectibles</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h3>DC</h3>
                    <ul>
                        <li>
                            <a href="#">Terms Of Use</a>
                        </li>
                        <li>
                            <a href="#">Privacy policy (new)</a>
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising</a>
                        </li>
                        <li>
                            <a href="#">Jobs</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="#">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h3>SITES</h3>
                    <ul>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Universe</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
                
            </div>
            <div class="col-2">
            </div>
        </div>
    </footer>
    <footer class="footer-bottom">
        <div class="container">
            <div class="button">
                <a href="#">SIGN-UP NOW!</a>
            </div>
            <div class="social">
                <h4>FOLLOW US</h4>
                <a href="#">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="#">
                    <i class="fa-brands fa-twitter"></i>
                </a>
                <a href="#">
                    <i class="fa-brands fa-youtube"></i>
                </a>
                <a href="#">
                    <i class="fa-brands fa-pinterest-p"></i>
                </a>
                <a href="#">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
            </div>
        </div>
    </footer>

</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables.scss" as *;

    .container{
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
    }

    .footer-top {
        background-color: #0282f9;
    }
    .footer-center {
        background-image: url(../assets/img/footer-bg.jpg);
        height: 100%;
        background-repeat: no-repeat;
        background-size: cover;
        .col-1 {
            display: flex;
            width: 30%;
            justify-content: space-between;
            padding-bottom: 50px;
        }
        h3 {
            color: white;
            font-weight: 700;
            font-size: 18px;
            margin: 20px 0;
        }
        ul {
            list-style: none;
            padding: 0;
            margin: 5px 0;
        }
        li {
            font-size: 12px;
            margin: 10px 0;
        }
        a {
            text-decoration: none;
            color: gray;
        }
    .col-2 {
        width: 50%;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-size: cover;
    }
    }
    .footer-bottom {
        background-color: #303030;
        padding: 40px;
    
        .button a {
            color: white;
            text-decoration: none;
            padding: 10px;
            border: 2px solid #0282f9;
            font-weight: 700;
        }
        .social h4 {
            color: #0282f9;
            font-weight: 700;
            display: inline-block;
        }
        .social a {
            text-decoration: none;
            background-color: #797979;
            padding: 10px;
            border-radius: 50%;
            margin-left: 15px;
        }
        .social i {
            color: #303030;
            font-size: 23px;
            display: inline-block;
        }

    }
</style>