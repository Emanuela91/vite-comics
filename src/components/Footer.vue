<script>
import TopFooterVue from './FooterContent/TopFooter.vue';
import MidFooterVue from './FooterContent/MidFooter.vue';
import BotFooterVue from './FooterContent/BotFooter.vue';

export default {
    name: "Footer",
    components: {
        TopFooterVue,
        MidFooterVue,
        BotFooterVue,
    }
}
</script>

<template>
    <footer>
        <TopFooterVue />
        <MidFooterVue />
        <BotFooterVue />
    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as*;
</style>