<template>
<div class="banner">
    <div class="container">
        <div class="card">
            <figure>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            </figure>
            <figcaption>DIGITAL COMICS</figcaption>
        </div>
        <div class="card">
            <figure>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
            </figure>
            <figcaption>DC MERCHANDISE</figcaption>
        </div>
        <div class="card">
            <figure>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            </figure>
            <figcaption>SUBSCRIPTION</figcaption>
        </div>
        <div class="card">
            <figure>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            </figure>
            <figcaption>COMIC SHOP LOCATOR</figcaption>
        </div>
        <div class="card">
            <figure>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            </figure>
            <figcaption>DC POWER VISA</figcaption>
        </div>
    </div>
</div>    
</template>

<script>
export default {
    name: 'TheBanner'
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
