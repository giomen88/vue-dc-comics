<template>
    <footer>
        <div class="top">
            <div class="container">
                <nav>
                    <div class="links">

                    </div>

                    <div class="logo">
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </nav>
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
                            <li><a href="">FOLLOW US</a></li>
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
    flex-basis: 450px;
    flex-shrink: 1;

    .top {
        height: 300px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-position: bottom center;
        background-size: cover;

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;

            .logo {
                width: 450px;
                align-self: flex-start;
            }
        }
    }


    .bottom {
        height: 150px;
        background-image: linear-gradient(#303030 120px, black 120px);
        position: relative;

        nav {
        padding-bottom: 50px;
        padding-top: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;    
        
            ul {
                display: flex;
                justify-content: space-between;
                align-items: center;
            }
        }
    }      
}
</style>