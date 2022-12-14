<script>
export default {
    name: "TopFooter"

}
</script>

<template>
    <section>
        <div class="container">
            <div class="link_card">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="DIGITAL COMICS">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="link_card">
                <img src="../../assets/img/buy-comics-merchandise.png" alt="DC MERCHANDISE">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="link_card">
                <img src="../../assets/img/buy-comics-subscriptions.png" alt="SUBSCRIPTIONS">
                <span>SUBSCRIPTIONS</span>
            </div>
            <div class="link_card">
                <img src="../../assets/img/buy-comics-shop-locator.png" alt="COMIC SHOP LOCATOR">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="link_card">
                <img src="../../assets/img/buy-dc-power-visa.svg" alt="DC POWER VISA">
                <span>DC POWER VISA</span>
            </div>
        </div>

    </section>

</template>

<style lang="scss" scoped>
@use '../../styles/partials/variables' as*;
@use '../../styles/partials/mixins' as*;

section {
    background-color: #0282f9;
    height: 100px;

    .container {
        @include center();
        justify-content: space-around;
        height: 100%;

        .link_card {
            display: flex;
            align-items: center;

            img {
                width: 45px;
                height: 40px;
                padding-right: 10px;
            }

            span {
                color: $primary;
                font-size: 12px;

            }
        }
    }


}
</style>