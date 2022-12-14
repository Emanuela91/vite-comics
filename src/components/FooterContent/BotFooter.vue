<script>
export default {
    name: "BotFooter"

}
</script>

<template>
    <section>
        <div class="container">
            <button>
                SIGN-UP NOW!
            </button>

            <div class="follow">
                <h3>FOLLOW US</h3>
                <div class="social">
                    <img src="../../assets/img/footer-facebook.png" alt="Facebook">
                    <img src="../../assets/img/footer-twitter.png" alt="Twitter">
                    <img src="../../assets/img/footer-youtube.png" alt="YouTube">
                    <img src="../../assets/img/footer-pinterest.png" alt="Pinterest">
                    <img src="../../assets/img/footer-periscope.png" alt="Periscope">
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/variables' as*;
@use '../../styles/partials/mixins' as*;

section {
    background-color: #303030;
    height: 80px;

    .container {
        @include between();
        height: 100%;

        button {
            padding: 10px;
            background-color: #303030;
            border-color: $fourth;
            color: $primary;
        }

        .follow {
            display: flex;
            align-items: center;

            h3 {
                font-size: 15px;
                color: $fourth;
                padding-right: 20px;
            }

            img {
                width: 30px;
                padding-right: 10px;
            }
        }
    }
}
</style>