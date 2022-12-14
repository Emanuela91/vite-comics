<script>
export default {
    name: "Header",
    data() {
        return {
            links: [
                {
                    text: "CHARACTERS",
                    url: "#",
                    current: false,
                },
                {
                    text: "COMICS",
                    url: "#",
                    current: true,
                },
                {
                    text: "MOVIES",
                    url: "#",
                    current: false,
                },
                {
                    text: "TV",
                    url: "#",
                    current: false,
                },
                {
                    text: "GAMES",
                    url: "#",
                    current: false,
                },
                {
                    text: "COLLECTIBLES",
                    url: "#",
                    current: false,
                },
                {
                    text: "VIDEOS",
                    url: "#",
                    current: false,
                },
                {
                    text: "FANS",
                    url: "#",
                    current: false,
                },
                {
                    text: "NEWS",
                    url: "#",
                    current: false,
                },
                {
                    text: "SHOP",
                    url: "#",
                    current: false,
                }
            ]
        }
    }
}

</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logoDC">
            </div>

            <nav>
                <ul>
                    <li v-for="(link, index) in links" key="index">
                        <a :class="{ active: link.current }" :href="link.url">
                            {{ link.text }}
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>

</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as*;
@use '../styles/partials/variables' as*;
@use '../styles/partials/mixins' as*;

header {
    img {
        height: 85px;
    }

    .container {
        @include between();

        nav {
            ul {
                @include center();

                li {
                    list-style: none;
                    margin-left: 15px;

                    a {
                        text-decoration: none;
                        font-size: 12px;
                        color: $secondary;
                        display: inline-block;
                        line-height: 100px;
                        font-weight: 600;

                        &.active,
                        &:hover {
                            color: #0282f9;
                            border-bottom: solid 5px #0282f9;
                        }
                    }
                }
            }
        }
    }

}
</style>