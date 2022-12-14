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
    height: 400px;

    img {
        background-size: cover;
        height: 100%;
        width: 100%;
        object-fit: cover;
        object-position: 0% 0%;
    }
}
</style>