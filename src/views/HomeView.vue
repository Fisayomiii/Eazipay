<template>
    <Header />
    <Hero />
    <Sectionone />
    <Sectiontwo />
    <Sectionthree />
    <Form />
    <Footer />
</template>

<script>
import Header from "../components/layout/Header.vue";
import Hero from "../components/layout/Hero.vue";
import Sectionone from "../components/layout/Sectionone.vue";
import Sectiontwo from "../components/layout/Sectiontwo.vue";
import Sectionthree from "../components/layout/Sectionthree.vue";
import Footer from "../components/layout/Footer.vue";
import Form from "../components/layout/Form.vue";
export default {
    components: { Header, Hero, Sectionone, Sectiontwo, Sectionthree, Form, Footer },
};
</script>