<script>
export default {
    name: "Card",
    props: {
        film: Object
    }
}
</script>

<template>
    <div class="card">
        <div>
            <img :src="film.thumb" :alt="film.series">
        </div>
        <h3>{{ film.series }}</h3>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as*;

.card {
    width: (calc(100% / 6 - 20px));
    margin: 20px 10px;

    img {
        height: 150px;
        width: 150px;
        object-fit: cover;
        object-position: 0% 0%;
    }

    h3 {
        color: $primary;
        padding-top: 5px;
    }
}
</style>