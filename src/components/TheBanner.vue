<template>
<div class="banner">
    <div class="container">
        <div 
        class="card"
        v-for="link in bannerLinks"
        :key="link.text">
            <figure>
                <img :src="link.url" :alt="link.text">
            </figure>
            <figcaption>{{link.text}}</figcaption>
        </div>
    </div>
</div>    
</template>

<script>
export default {
    name: 'TheBanner',

    data() {
        return {
            bannerLinks: [
                {
                    text: "DIGITAL COMICS",
                    url: require("../assets/img/buy-comics-digital-comics.png"),
                },
                {
                    text: "DC MERCHANDISE",
                    url:  require("../assets/img/buy-comics-merchandise.png"),
                },
                {
                    text: "SUBSCRIPTION",
                    url:  require("../assets/img/buy-comics-subscriptions.png"),
                },
                {
                    text: "COMIC SHOP LOCATOR",
                    url: require( "../assets/img/buy-comics-shop-locator.png"),
                },
                {
                    text: "DC POWER VISA",
                    url:  require("../assets/img/buy-dc-power-visa.svg"),
                }
            ]

        }
    },
 
}
</script>

<style lang="scss" scoped>
.banner {
    height: 120px;
    background-color: #0C7CEC;
    position: relative;

    .container {
        display: flex;
        justify-content: space-between;
    }

    .card {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        color: #fcfcfc;
        font-size: 0.8rem;

        img {
            width: 30px;
            margin-right: 10px;
        }
    }

}
</style>
