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