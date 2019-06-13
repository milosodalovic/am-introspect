<template>
    <section id="one">
        <div class="inner">
            <header>
                <h2>Magna Etiam Lorem</h2>
            </header>
            <p>
                Suspendisse mauris. Fusce accumsan mollis eros. Pellentesque a diam sit amet mi ullamcorper vehicula.
                Integer adipiscin sem. Nullam quis massa sit amet nibh viverra malesuada. Nunc sem lacus, accumsan quis,
                faucibus non, congue vel, arcu, erisque hendrerit tellus. Integer sagittis. Vivamus a mauris eget arcu
                gravida tristique. Nunc iaculis mi in ante.
            </p>
            <ul class="actions">
                <li><a href="#" class="button alt">Learn More</a></li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import url(../assets/css/font-awesome.min.css);
@import url("https://fonts.googleapis.com/css?family=Lato:300,400,700|Pacifico");

div,
h2,
p,
a,
ul,
li,
header,
section {
    font-family: "Lato", sans-serif;
}

section .inner {
    max-width: 65em;
    width: calc(100% - 6em);
    margin: 0 auto;
}

h2 {
    font-weight: 700;
    line-height: 1.5;
    margin: 0 0 1em 0;
    text-transform: uppercase;
    color: #e5474b;
    font-size: 1.75em;
}

.button {
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

    &.alt {
        background-color: transparent;
        box-shadow: inset 0 0 0 2px #e5474b;
        color: #e5474b !important;
        &:hover {
            background: #fceced;
        }
    }
}

ul {
    list-style: none;
    margin: 0 0 2em 0;
    padding-left: 1em;
    li {
        padding-left: 0.5em;
    }
    &.actions {
        padding-left: 0;
        li {
            padding: 0 1em 0 0;
        }
    }
}

p {
    font-weight: 300;
    line-height: 2;
    margin: 0 0 2em 0;
}

@media screen and (max-width: 736px) {
    h2 {
        font-size: 1.25em;
    }
}
@media screen and (max-width: 480px) {
    section .inner {
        max-width: 90%;
        width: 90%;
    }
}

#one {
    padding: 6em 0 4em 0;
}

@media screen and (max-width: 980px) {
    #one {
        padding: 4em 0 2em 0;
    }
}

@media screen and (max-width: 736px) {
    #one {
        padding: 2em 0 0.1em 0;
    }
}
</style>


