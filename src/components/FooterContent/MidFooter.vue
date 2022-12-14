<script>
export default {
    name: "MidFooter"

}
</script>

<template>
    <section>
        <div class="container">
            <div class="first_column">
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

                <h3>SHOP</h3>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>

            </div>

            <div class="second_column">
                <h3>DC</h3>
                <ul>
                    <li>Term Of Use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choises</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshop</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>

            <div class="third_column">
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
    </section>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/variables' as*;

section {
    background-image: url('../../assets/img/footer-bg.jpg');
    height: 300px;

    .container {
        display: flex;
        padding-top: 30px;

        div {
            padding-right: 25px;

            h3 {
                font-size: 15px;
                color: $primary;
                padding: 10px 0;
            }

            ul {
                li {
                    list-style: none;
                    color: $third;
                    font-size: 12px;
                    line-height: 18px;
                }
            }
        }
    }
}
</style>