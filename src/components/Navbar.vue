<template>
    <header id="header">
        <div class="inner">
            <a href="index.html" class="logo">introspect</a>
            <nav id="nav">
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

<style lang="scss" scoped>
@import url(../assets/css/font-awesome.min.css);
@import url("https://fonts.googleapis.com/css?family=Lato:300,400,700|Pacifico");
div,
a,
header,
nav {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

header,
nav {
    display: block;
}

* {
    box-sizing: border-box;
    &:before,
    &:after {
        box-sizing: border-box;
    }
}

a {
    transition: color 0.2s ease-in-out;
    text-decoration: none;
}
a:hover {
    text-decoration: underline;
}
a {
    color: #e5474b;
}

#header {
    background: #1c1c1c;
    color: #d5d5d5;
    cursor: default;
    height: 5em;
    left: 0;
    line-height: 5em;
    position: fixed;
    text-align: right;
    top: 0;
    width: 100%;
    z-index: 10001;
    .inner {
        max-width: 65em;
        width: calc(100% - 6em);
        margin: 0 auto;
        position: relative;
    }
    .logo {
        font-family: "Pacifico", cursive;
        display: inline-block;
        height: inherit;
        left: 0;
        line-height: inherit;
        margin: 0;
        padding: 0;
        position: absolute;
        top: 0;
        color: #e5474b;
        font-size: 1.75em;
        text-transform: none;
        font-weight: normal;
        padding: 0;
        &:hover {
            color: rgba(229, 71, 75, 0.75);
        }
    }
    a {
        transition: color 0.2s ease-in-out;
        display: inline-block;
        padding: 0 2em;
        color: #ffffff;
        text-decoration: none;
        text-transform: uppercase;
        font-weight: 700;
        font-size: 0.85em;
        &:hover {
            color: rgba(255, 255, 255, 0.75);
        }
        &:last-child {
            padding-right: 0em;
        }
    }
}

@media screen and (max-width: 480px) {
    #header .inner {
        max-width: 90%;
        width: 90%;
    }
}

@media screen and (max-width: 736px) {
    #header a {
        padding: 0 0.5em;
    }
}

@media screen and (max-width: 480px) {
    #header {
        min-width: 320px;
    }
}

#nav {
    display: inline-block;
}

@media screen and (max-width: 980px) {
    #nav {
        display: none;
    }
}

.navPanelToggle {
    position: fixed;
    text-decoration: none;
    height: 4em;
    right: 3em;
    top: 0.75em;
    width: 4em;
    display: none;
    z-index: 10002;
    &:before {
        -moz-osx-font-smoothing: grayscale;
        -webkit-font-smoothing: antialiased;
        font-family: FontAwesome;
        font-style: normal;
        font-weight: normal;
        text-transform: none !important;
        color: #fff;
        display: block;
        font-size: 16px;
        height: 2.25em;
        left: 0.5em;
        line-height: 2.25em;
        position: absolute;
        text-align: center;
        top: 0.5em;
        width: 3.5em;
    }
    *:before {
        color: #fff;
        display: block;
        font-size: 16px;
        height: 2.25em;
        left: 0.5em;
        line-height: 2.25em;
        position: absolute;
        text-align: center;
        top: 0.5em;
        width: 3.5em;
    }
}

@media screen and (max-width: 980px) {
    .navPanelToggle {
        display: block;
    }
}

@media screen and (max-width: 736px) {
    .navPanelToggle {
        right: 1em;
    }
}

#navPanel {
    transform: translatex(20em);
    transition: transform 0.2s ease-in-out, visibility 0.2s ease-in-out;
    -webkit-overflow-scrolling: touch;
    visibility: hidden;
    overflow-y: auto;
    position: fixed;
    right: 0;
    top: 0;
    background: #1c1c1c;
    color: #fff;
    height: 100%;
    max-width: 80%;
    width: 20em;
    padding: 1.5em;
    text-transform: uppercase;
    z-index: 10003;
    display: none;
    &.visible {
        transform: translatex(0);
        box-shadow: 0 0 1.5em 0 rgba(0, 0, 0, 0.2);
        visibility: visible;
    }
    a:not(.close) {
        border-top: solid 1px rgba(255, 255, 255, 0.1);
        color: #fff;
        font-weight: 700;
        display: block;
        padding: 0.75em 0;
        text-decoration: none;
        &:first-child {
            border: none;
        }
    }
    .close {
        text-decoration: none;
        transition: color 0.2s ease-in-out;
        border: 0;
        color: #484848;
        cursor: pointer;
        display: block;
        height: 4em;
        padding-right: 1.25em;
        position: absolute;
        right: 0;
        text-align: right;
        top: 0;
        width: 5em;
        &:before {
            -moz-osx-font-smoothing: grayscale;
            -webkit-font-smoothing: antialiased;
            font-family: FontAwesome;
            font-style: normal;
            font-weight: normal;
            text-transform: none !important;
            content: "\f00d";
            width: 3em;
            height: 3em;
            line-height: 3em;
            display: block;
            position: absolute;
            right: 0;
            top: 0;
            text-align: center;
        }
        &:hover {
            color: inherit;
        }
    }
}

@media screen and (max-width: 980px) {
    #navPanel {
        display: block;
    }
}

.icon {
    text-decoration: none;
    border-bottom: none;
    position: relative;
    &:before {
        -moz-osx-font-smoothing: grayscale;
        -webkit-font-smoothing: antialiased;
        font-family: FontAwesome;
        font-style: normal;
        font-weight: normal;
        text-transform: none !important;
    }
    > .label {
        display: none;
    }
}
</style>