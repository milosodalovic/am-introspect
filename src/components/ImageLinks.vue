<template>
    <section id="two">
        <div class="inner">
            <article>
                <div class="content">
                    <header>
                        <h3>Pellentesque adipis</h3>
                    </header>
                    <div class="image fit">
                        <img src="../images/pic01.jpg" alt="" />
                    </div>
                    <p>
                        Cumsan mollis eros. Pellentesque a diam sit amet mi magna ullamcorper vehicula. Integer
                        adipiscin sem. Nullam quis massa sit amet lorem ipsum feugiat tempus.
                    </p>
                </div>
            </article>
            <article class="alt">
                <div class="content">
                    <header>
                        <h3>Morbi interdum mol</h3>
                    </header>
                    <div class="image fit">
                        <img src="../images/pic02.jpg" alt="" />
                    </div>
                    <p>
                        Cumsan mollis eros. Pellentesque a diam sit amet mi magna ullamcorper vehicula. Integer
                        adipiscin sem. Nullam quis massa sit amet lorem ipsum feugiat tempus.
                    </p>
                </div>
            </article>
        </div>
    </section>
</template>

<style lang="scss" scoped>
div,
h3,
p,
img,
article,
header,
section {
    font-family: "Lato", sans-serif;
}

p {
    margin: 0 0 2em 0;
    font-weight: 300;
    line-height: 2;
}

h3 {
    font-weight: 700;
    line-height: 1.5;
    margin: 0 0 1em 0;
    text-transform: uppercase;
    font-size: 1.35em;
    color: #e5474b;
}

.image {
    &.fit {
        display: block;
        margin: 0 0 2em 0;
        width: 100%;
        img {
            width: 100%;
        }
    }
}

section .inner {
    max-width: 65em;
    width: calc(100% - 6em);
    margin: 0 auto;
}

#two {
    padding: 6em 0 4em 0;
    background: linear-gradient(to right, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);

    .inner {
        display: flex;

        flex-direction: row;
        article {
            width: 50%;
            &:first-child {
                padding-right: 6em;
            }
            &:last-child {
                padding-left: 6em;
            }
        }
    }
}

@media screen and (max-width: 980px) {
    #two {
        background: linear-gradient(to bottom, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
        padding: 4em 0 2em 0;
        .inner {
            flex-direction: column;
            article {
                width: 100%;
                &:first-child {
                    padding-right: 0;
                    padding-bottom: 2em;
                }
                &:last-child {
                    padding-left: 0;
                    padding-top: 2em;
                }
            }
        }
    }
}

@media screen and (max-width: 480px) {
    section .inner {
        max-width: 90%;
        width: 90%;
    }
}
@media screen and (max-width: 736px) {
    #two {
        padding: 2em 0 0.1em 0;
    }
}

@media screen and (max-width: 736px) {
    h3 {
        font-size: 1.1em;
    }
}
</style>
