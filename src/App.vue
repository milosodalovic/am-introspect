<template>
    <div id="app">
        <title>Introspect by TEMPLATED, Codeus</title>
        <navbar></navbar>
        <!-- <hero></hero> -->
        <!-- <learn-more></learn-more> -->
        <!-- <image-links></image-links> -->
        <!-- <icon-links></icon-links> -->
        <!-- <intro-form></intro-form> -->
    </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import IconLinks from "./components/IconLinks.vue";
import ImageLinks from "./components/ImageLinks.vue";
import IntroForm from "./components/IntroForm.vue";
import LearnMore from "./components/LearnMore.vue";
import Navbar from "./components/Navbar.vue";

export default {
    name: "app",
    components: {
        IntroForm,
        Hero,
        IconLinks,
        ImageLinks,
        LearnMore,
        Navbar
    }
};
</script>
