<script>
export default {};
</script>

<template>
    <section class="bottom-footer">
        <div class="container">
            <button type="button">SIGN-UP NOW</button>

            <div class="bottom-right-footer">
                <h3 class="me">FOLLOW US</h3>
                <img class="me" src="../assets/img/footer-facebook.png" alt="facebook">
                <img class="me" src="../assets/img/footer-twitter.png" alt="twitter">
                <img class="me" src="../assets/img/footer-youtube.png" alt="youtube">
                <img class="me" src="../assets/img/footer-pinterest.png" alt="pinterest">
                <img class="me" src="../assets/img/footer-periscope.png" alt="periscope">
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.bottom-footer {
    background-color: #303030;

    .container {
        justify-content: space-between;
        align-items: center;
        padding: 20px;
    }

    button {
        background-color: transparent;
        color: #fff;
        padding: 10px;
        font-size: 13px;
        border-color: #0282f9;
        cursor: pointer;
    }

    .bottom-right-footer {
        display: flex;
        align-items: center;

        h3 {
            color: #0282f9;
            font-size: 13px;
        }

        img {
            width: 20px;
        }

        .me {
            margin-right: 15px;
        }
    }
}
</style>