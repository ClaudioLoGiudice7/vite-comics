<script>
export default {};
</script>

<template>
    <section class="upper-footer">

        <div class="container">
            <div class="upper-footer-links">
                <div>
                    <h3>DC COMICS</h3>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>

                    <h3 class="mt">SHOP</h3>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>

                <div>
                    <h3>DC</h3>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy Policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>

                <div>
                    <h3>SITES</h3>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>

            <div class="upper-footer-logo"></div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.upper-footer {
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    color: #fff;

    .container {
        justify-content: space-between;

        .upper-footer-links {
            display: flex;
            justify-content: space-between;
            width: 50%;
            padding: 50px;

            h3 {
                font-size: 18px;
                font-weight: bold;
                margin-bottom: 10px;
            }

            .mt {
                margin-top: 50px;
            }

            ul {
                font-size: 11px;
                line-height: 20px;
            }
        }

        .upper-footer-logo {
            background-image: url("../assets/img/dc-logo-bg.png");
            height: 400px;
            width: 670px;
        }
    }
}
</style>