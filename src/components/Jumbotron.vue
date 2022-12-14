<script>
export default {
    name: "Jumbotron",
}
</script>

<template>
    <section>
        <img src="../assets/img/jumbotron.jpg" alt="Jumbotron">
    </section>
</template>

<style lang="scss" scoped>
section {
    min-height: 200px;

    img {
        background-size: cover;
        height: 100%;
        width: 100%;
    }
}
</style>