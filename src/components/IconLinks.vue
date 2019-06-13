<template>
    <section id="three">
        <div class="inner">
            <article>
                <div class="content">
                    <span class="icon fa-laptop"></span>
                    <header>
                        <h3>Tempus Feugiat</h3>
                    </header>
                    <p>
                        Morbi interdum mollis sapien. Sed ac risus. Phasellus lacinia, magna lorem ullamcorper laoreet,
                        lectus arcu.
                    </p>
                    <ul class="actions">
                        <li><a href="#" class="button alt">Learn More</a></li>
                    </ul>
                </div>
            </article>
            <article>
                <div class="content">
                    <span class="icon fa-diamond"></span>
                    <header>
                        <h3>Aliquam Nulla</h3>
                    </header>
                    <p>
                        Ut convallis, sem sit amet interdum consectetuer, odio augue aliquam leo, nec dapibus tortor
                        nibh sed.
                    </p>
                    <ul class="actions">
                        <li><a href="#" class="button alt">Learn More</a></li>
                    </ul>
                </div>
            </article>
            <article>
                <div class="content">
                    <span class="icon fa-laptop"></span>
                    <header>
                        <h3>Sed Magna</h3>
                    </header>
                    <p>
                        Suspendisse mauris. Fusce accumsan mollis eros. Pellentesque a diam sit amet mi ullamcorper
                        vehicula.
                    </p>
                    <ul class="actions">
                        <li><a href="#" class="button alt">Learn More</a></li>
                    </ul>
                </div>
            </article>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import url(../assets/css/font-awesome.min.css);

html,
body,
div,
span,
h3,
p,
a,
ul,
li,
header,
section {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

header,
section {
    display: block;
    line-height: 2;
}

body {
    background: #fff;
    &.is-loading * {
        animation: none !important;
        transition: none !important;
        &:before,
        &:after {
            animation: none !important;
            transition: none !important;
        }
    }
    background-color: #fff;
    color: #111111;
    font-family: "Lato", sans-serif;
    font-size: 15pt;
    font-weight: 300;
    position: relative;
    padding-top: 5em;
}

@media screen and (max-width: 480px) {
    html,
    body {
        min-width: 320px;
    }
}

@media screen and (max-width: 1680px) {
    body {
        font-size: 13pt;
    }
}

@media screen and (max-width: 1280px) {
    body {
        font-size: 13pt;
    }
}

@media screen and (max-width: 980px) {
    body {
        font-size: 12pt;
    }
}

@media screen and (max-width: 736px) {
    body {
        font-size: 12pt;
    }
}

@media screen and (max-width: 480px) {
    body {
        font-size: 12pt;
    }
}

ul {
    list-style: none;
}

* {
    box-sizing: border-box;
    &:before,
    &:after {
        box-sizing: border-box;
    }
}

@-ms-viewport {
    width: device-width;
}

a {
    transition: color 0.2s ease-in-out;
    text-decoration: none;
    &:hover {
        text-decoration: underline;
    }
    color: #e5474b;
}

p {
    margin: 0 0 2em 0;
}

h3 {
    font-weight: 700;
    line-height: 1.5;
    margin: 0 0 1em 0;
    text-transform: uppercase;
    font-size: 1.35em;
    color: #e5474b;
}

h3 a {
    color: inherit;
    text-decoration: none;
}

@media screen and (max-width: 736px) {
    h3 {
        font-size: 1.1em;
    }
}

.button {
    appearance: none;
    transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
    border-radius: 0;
    border: 0;
    cursor: pointer;
    display: inline-block;
    font-size: 0.8em;
    font-weight: 700;
    height: 3.5em;
    line-height: 3.65em;
    padding: 0 2.25em;
    text-align: center;
    text-decoration: none;
    text-transform: uppercase;
    white-space: nowrap;
    background-color: #5a5a5a;
    color: #ffffff !important;
}

.button:hover {
    text-decoration: none;
    background-color: #676767;
}

.button.icon {
    padding-left: 1.35em;
}

.button.icon:before {
    margin-right: 0.5em;
}

.button.fit {
    display: block;
    margin: 0 0 1em 0;
    width: 100%;
}

.button.small {
    font-size: 0.8em;
}

.button.big {
    font-size: 1.35em;
}

.button {
    &.disabled,
    &:disabled {
        pointer-events: none;
        opacity: 0.25;
    }
}

.button:active {
    background-color: #4d4d4d;
}

.button.alt {
    background-color: transparent;
    box-shadow: inset 0 0 0 2px #e5474b;
    color: #e5474b !important;
}

.button.alt:hover {
    background: #fceced;
}

.button.alt:active {
    background-color: #f9dadb;
}

.button.alt.icon:before {
    color: #717171;
}

.button.special {
    background-color: #e5474b;
    color: #ffffff !important;
}

.button.special:hover {
    background-color: #e85d61;
}

.button.special:active {
    background-color: #e23135;
}

.icon {
    text-decoration: none;
    border-bottom: none;
    position: relative;
    &:before {
        font-family: FontAwesome;
        font-style: normal;
        font-weight: normal;
        text-transform: none !important;
    }
    > .label {
        display: none;
    }
}

ul {
    list-style: disc;
    margin: 0 0 2em 0;
    padding-left: 1em;
    li {
        padding-left: 0.5em;
    }
    &.alt {
        list-style: none;
        padding-left: 0;
        li {
            border-top: solid 1px;
            padding: 0.5em 0;
            &:first-child {
                border-top: 0;
                padding-top: 0;
            }
        }
    }
    &.icons {
        cursor: default;
        list-style: none;
        padding-left: 0;
        li {
            display: inline-block;
            padding: 0 1em 0 0;
            &:last-child {
                padding-right: 0;
            }
            .icon:before {
                font-size: 2em;
            }
        }
    }
    &.actions {
        cursor: default;
        list-style: none;
        padding-left: 0;
        li {
            display: inline-block;
            padding: 0 1em 0 0;
            vertical-align: middle;
            &:last-child {
                padding-right: 0;
            }
        }
        &.small li {
            padding: 0 0.5em 0 0;
        }
        &.vertical {
            li {
                display: block;
                padding: 1em 0 0 0;
                &:first-child {
                    padding-top: 0;
                }
                > * {
                    margin-bottom: 0;
                }
            }
            &.small li {
                padding: 0.5em 0 0 0;
                &:first-child {
                    padding-top: 0;
                }
            }
        }
        &.fit {
            display: table;
            margin-left: -1em;
            padding: 0;
            table-layout: fixed;
            width: calc(100% + 1em);
            li {
                display: table-cell;
                padding: 0 0 0 1em;
                > * {
                    margin-bottom: 0;
                }
            }
            &.small {
                margin-left: -0.5em;
                width: calc(100% + 0.5em);
                li {
                    padding: 0 0 0 0.5em;
                }
            }
        }
    }
}

ul.alt li {
    border-top-color: #e5474b;
}

section .inner {
    max-width: 65em;
    width: calc(100% - 6em);
    margin: 0 auto;
}

@media screen and (max-width: 480px) {
    section .inner {
        max-width: 90%;
        width: 90%;
    }
}

header {
    p {
        position: relative;
        margin: 0 0 1.5em 0;
    }
    h3 + p {
        font-size: 1.1em;
        margin-top: -0.8em;
    }
    p {
        color: #717171;
    }
}

#three {
    padding: 6em 0 4em 0;
    .inner {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        article {
            width: 26%;
            display: block;
            p {
                color: #717171;
            }
            .icon {
                color: #b3b3b3;
                font-size: 3em;
            }
        }
    }
}

@media screen and (max-width: 980px) {
    #three .inner {
        flex-direction: column;
        article {
            width: 100%;
            margin: 0 auto;
        }
    }
}

@media screen and (max-width: 980px) {
    #three {
        padding: 4em 0 2em 0;
    }
}

@media screen and (max-width: 736px) {
    #three {
        padding: 2em 0 0.1em 0;
    }
}
</style>