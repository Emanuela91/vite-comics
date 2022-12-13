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

</template>

<style lang="scss">
@use '../styles/general.scss' as*;
@use '../styles/partials/variables' as*;
</style>