<template>
    <footer>
        <div class="top">
            <div class="container">

                        <nav>
                            <div class="col dc-comics">
                            <p>DC COMICS</p>
                                <ul>
                                    <li><a href="">Characters</a></li>
                                    <li><a href="">Comics</a></li>
                                    <li><a href="">Movies</a></li>
                                    <li><a href="">TV</a></li>
                                    <li><a href="">Games</a></li>
                                    <li><a href="">Videos</a></li>
                                    <li><a href="">News</a></li>
                                        <p>SHOP</p>
                                    <ul class="shop">
                                        <li><a href="">Shop DC</a></li>
                                        <li><a href="">Shop DC Collectibles</a></li>
                                    </ul>
                                </ul>
                            </div>
                            <div class="col dc">
                                <p>DC</p>
                                <ul>
                                    <li><a href="">Terms of use</a></li>
                                    <li><a href="">Privacy policy (New)</a></li>
                                    <li><a href="">Add choices</a></li>
                                    <li><a href="">Advertising</a></li>
                                    <li><a href="">Jobs</a></li>
                                    <li><a href="">Subscription</a></li>
                                    <li><a href="">Talent Workshops</a></li>
                                    <li><a href="">CPSC Certificates</a></li>
                                    <li><a href="">Ratings</a></li>
                                    <li><a href="">Shop Help</a></li>
                                    <li><a href="">Contact Us</a></li>
                                </ul>
                            </div>

                            <div class="col sites">
                                <p>SITES</p>
                                <ul>
                                    <li><a href="">DC</a></li>
                                    <li><a href="">MAD Magazine</a></li>
                                    <li><a href="">DC Kids</a></li>
                                    <li><a href="">DC Universe</a></li>
                                    <li><a href="">DC Power Visa</a></li>
                                </ul>
                            </div>
                        </nav>

                    <div class="big-logo">
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
            </div>
        </div>

        <div class="bottom">
            <div class="container">
                <nav>
                     <div>
                        <button>SIGN-UP NOW!</button>
                    </div>

                    <div class="social">
                         <ul>
                            <li><a class="follow" href="">FOLLOW US</a></li>
                            <li><a href=""><img src="../assets/img/footer-facebook.png" alt="facebook-icon"></a></li>
                            <li><a href=""><img src="../assets/img/footer-twitter.png" alt="twitter-icon"></a></li>
                            <li><a href=""><img src="../assets/img/footer-youtube.png" alt="youtube-icon"></a></li>
                            <li><a href=""><img src="../assets/img/footer-pinterest.png" alt="pinterest-icon"></a></li>
                            <li><a href=""><img src="../assets/img/footer-periscope.png" alt="periscope-icon"></a></li>
                        </ul>
                    </div>
                </nav>
            </div>
        </div>

    </footer>
</template>

<script>
export default {
    name: 'TheFooter',
}
</script>


<style lang="scss" scoped>
footer {
    height: 400px;

    .top {
        height: 300px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-position: bottom;
        background-size: cover;

        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;


            nav {
                color:#fcfcfc;
                display: flex;
                justify-content: space-between;
                align-items: flex-start;

                .col {
                    margin: 10px 10px;
                }

                p {
                    font-weight: bold;
                    margin-bottom: 5px;
                }

                a {
                    font-size: 0.8rem;
                    color: #808080;
                }
            }

            .big-logo {
                width: 398px;
                align-self: flex-start;
            }
        }
    }

    .bottom {
        height: 100px;
        background-image: linear-gradient(#303030 90px, #000000 90px);
        position: relative;

        nav {
        padding-bottom: 10px;
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;    

            button {
                background-color: transparent;
                border: 2px solid #0C7CEC;
                color: #fcfcfc;
                font-weight: bold;
                padding: 10px;
                cursor: pointer;
            }
            ul {
                display: flex;
                justify-content: space-between;
                align-items: center;

                li {
                    margin: 0 10px;

                    .follow {
                        font-weight: bold;
                        color: #0C7CEC;
                    }
                }
            }
        }
    }      
}
</style>