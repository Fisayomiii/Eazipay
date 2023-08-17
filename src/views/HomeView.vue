<template>
    <Hero />
    <Sectionone />
    <Sectiontwo />
    <Sectionthree />
</template>

<script>
import Hero from "../components/layout/Hero.vue";
import Sectionone from "../components/layout/Sectionone.vue";
import Sectiontwo from "../components/layout/Sectiontwo.vue";
import Sectionthree from "../components/layout/Sectionthree.vue";
export default {
    components: { Hero, Sectionone, Sectiontwo, Sectionthree },
};
</script>