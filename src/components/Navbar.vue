<template>
    <header id="header">
        <div class="inner">
            <a href="index.html" class="logo">introspect</a>
            <nav id="nav" class="test">
                <a href="index.html">Home</a>
                <a href="generic.html">Generic</a>
                <a href="elements.html">Elements</a>
            </nav>
        </div>
        <a href="#menu" class="navPanelToggle"><span class="fa fa-bars"></span></a>
    </header>
</template>

<script>
export default {};
</script>


<style lang="scss">
@import url(../assets/css/main.css);

.test {
    @media screen and (max-width: 600px) {
        visibility: hidden;
    }
}
</style>