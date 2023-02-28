<script>
export default {};
</script>

<template>
    <section class="blueBar">
        <div class="container">
            <div class="img-span-container">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
                <span>DIGITAL COMICS</span>
            </div>

            <div class="img-span-container">
                <img src="../assets/img/buy-comics-merchandise.png" alt="dc merchandise">
                <span>DC MERCHANDISE</span>
            </div>

            <div class="img-span-container">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">
                <span>SUBSCRIPTION</span>
            </div>

            <div class="img-span-container">
                <img id="shop-locator" src="../assets/img/buy-comics-shop-locator.png" alt="comic shop locator">
                <span>COMIC SHOP LOCATOR</span>
            </div>

            <div class="img-span-container">
                <img id="power-visa" src="../assets/img/buy-dc-power-visa.svg" alt="dc power visa">
                <span>DC POWER VISA</span>
            </div>

        </div>
    </section>
</template>

<style lang="scss" scoped>
.blueBar {
    background-color: #0282f9;

    .container {
        justify-content: center;
        align-items: center;
        color: #fff;
        height: 120px;
        // padding-left: 165px;
        margin: auto;

        .img-span-container {
            padding: 20px;

            img {
                width: 25%;
            }

            #power-visa {
                width: 15%;
            }

            #shop-locator {
                width: 15%;
            }

            span {
                font-size: 10px;
                margin-left: 15px;
                vertical-align: middle;
            }
        }
    }
}
</style>