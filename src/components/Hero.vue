<template>
    <section id="banner">
        <div class="inner">
            <h1>
                Introspect:
                <span
                    >A free + fully responsive<br />
                    site template by TEMPLATED</span
                >
            </h1>
            <ul class="actions">
                <li><a href="#" class="button alt">Get Started</a></li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
// @import url(../assets/css/font-awesome.min.css);

// html,
// body,
// div,
// span,
// h1,
// a,
// ul,
// li,
// section {
//     margin: 0;
//     padding: 0;
//     border: 0;
//     font-size: 100%;
//     font: inherit;
//     vertical-align: baseline;
// }

// section {
//     display: block;
// }

// body {
//     line-height: 1;
// }

// ul {
//     list-style: none;
// }

// body {
//     -webkit-text-size-adjust: none;
// }

// *,
// *:before,
// *:after {
//     -moz-box-sizing: border-box;
//     -webkit-box-sizing: border-box;
//     box-sizing: border-box;
// }

// body {
//     background-color: #fff;
//     color: #111111;
// }

// body {
//     font-family: "Lato", sans-serif;
//     font-size: 15pt;
//     font-weight: 300;
//     line-height: 2;
// }

// @media screen and (max-width: 1680px) {
//     body {
//         font-size: 13pt;
//     }
// }

// @media screen and (max-width: 1280px) {
//     body {
//         font-size: 13pt;
//     }
// }

// @media screen and (max-width: 980px) {
//     body {
//         font-size: 12pt;
//     }
// }

// @media screen and (max-width: 736px) {
//     body {
//         font-size: 12pt;
//     }
// }

// @media screen and (max-width: 480px) {
//     body {
//         font-size: 12pt;
//     }
// }

// a {
//     -moz-transition: color 0.2s ease-in-out;
//     -webkit-transition: color 0.2s ease-in-out;
//     -ms-transition: color 0.2s ease-in-out;
//     transition: color 0.2s ease-in-out;
//     text-decoration: none;
// }

// a:hover {
//     text-decoration: underline;
// }

// h1 {
//     font-weight: 700;
//     line-height: 1.5;
//     margin: 0 0 1em 0;
//     text-transform: uppercase;
// }

// h1 a {
//     color: inherit;
//     text-decoration: none;
// }

// h1 {
//     font-size: 2em;
//     margin: 0 0 0.25em 0;
// }

// @media screen and (max-width: 736px) {
//     h1 {
//         font-size: 1.5em;
//     }
// }

// a {
//     color: #e5474b;
// }

// h1 {
//     color: #e5474b;
// }

// // Button
// :root {
//     .button {
//         -moz-appearance: none;
//         -webkit-appearance: none;
//         -ms-appearance: none;
//         appearance: none;
//         -moz-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
//         -webkit-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
//         -ms-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
//         transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
//         border-radius: 0;
//         border: 0;
//         cursor: pointer;
//         display: inline-block;
//         font-size: 0.8em;
//         font-weight: 700;
//         height: 3.5em;
//         line-height: 3.65em;
//         padding: 0 2.25em;
//         text-align: center;
//         text-decoration: none;
//         text-transform: uppercase;
//         white-space: nowrap;
//     }

//     button:hover,
//     .button:hover {
//         text-decoration: none;
//     }

//     button.fit,
//     .button.fit {
//         display: block;
//         margin: 0 0 1em 0;
//         width: 100%;
//     }

//     button.small,
//     .button.small {
//         font-size: 0.8em;
//     }

//     input[type="submit"].big,
//     input[type="reset"].big,
//     input[type="button"].big,
//     button.big,
//     .button.big {
//         font-size: 1.35em;
//     }

//     input[type="submit"].disabled,
//     input[type="submit"]:disabled,
//     input[type="reset"].disabled,
//     input[type="reset"]:disabled,
//     input[type="button"].disabled,
//     input[type="button"]:disabled,
//     button.disabled,
//     button:disabled,
//     .button.disabled,
//     .button:disabled {
//         -moz-pointer-events: none;
//         -webkit-pointer-events: none;
//         -ms-pointer-events: none;
//         pointer-events: none;
//         opacity: 0.25;
//     }

//     input[type="submit"],
//     input[type="reset"],
//     input[type="button"],
//     button,
//     .button {
//         background-color: #5a5a5a;
//         color: #ffffff !important;
//     }

//     input[type="submit"]:hover,
//     input[type="reset"]:hover,
//     input[type="button"]:hover,
//     button:hover,
//     .button:hover {
//         background-color: #676767;
//     }

//     input[type="submit"]:active,
//     input[type="reset"]:active,
//     input[type="button"]:active,
//     button:active,
//     .button:active {
//         background-color: #4d4d4d;
//     }

//     input[type="submit"].alt,
//     input[type="reset"].alt,
//     input[type="button"].alt,
//     button.alt,
//     .button.alt {
//         background-color: transparent;
//         box-shadow: inset 0 0 0 2px #e5474b;
//         color: #e5474b !important;
//     }

//     input[type="submit"].alt:hover,
//     input[type="reset"].alt:hover,
//     input[type="button"].alt:hover,
//     button.alt:hover,
//     .button.alt:hover {
//         background: #fceced;
//     }

//     input[type="submit"].alt:active,
//     input[type="reset"].alt:active,
//     input[type="button"].alt:active,
//     button.alt:active,
//     .button.alt:active {
//         background-color: #f9dadb;
//     }

//     input[type="submit"].alt.icon:before,
//     input[type="reset"].alt.icon:before,
//     input[type="button"].alt.icon:before,
//     button.alt.icon:before,
//     .button.alt.icon:before {
//         color: #717171;
//     }

//     input[type="submit"].special,
//     input[type="reset"].special,
//     input[type="button"].special,
//     button.special,
//     .button.special {
//         background-color: #e5474b;
//         color: #ffffff !important;
//     }

//     input[type="submit"].special:hover,
//     input[type="reset"].special:hover,
//     input[type="button"].special:hover,
//     button.special:hover,
//     .button.special:hover {
//         background-color: #e85d61;
//     }

//     input[type="submit"].special:active,
//     input[type="reset"].special:active,
//     input[type="button"].special:active,
//     button.special:active,
//     .button.special:active {
//         background-color: #e23135;
//     }
// }

// // List
// :root {
//     ol {
//         list-style: decimal;
//         margin: 0 0 2em 0;
//         padding-left: 1.25em;
//     }

//     ol li {
//         padding-left: 0.25em;
//     }

//     ul {
//         list-style: disc;
//         margin: 0 0 2em 0;
//         padding-left: 1em;
//     }

//     ul li {
//         padding-left: 0.5em;
//     }

//     ul.alt {
//         list-style: none;
//         padding-left: 0;
//     }

//     ul.alt li {
//         border-top: solid 1px;
//         padding: 0.5em 0;
//     }

//     ul.alt li:first-child {
//         border-top: 0;
//         padding-top: 0;
//     }

//     ul.icons {
//         cursor: default;
//         list-style: none;
//         padding-left: 0;
//     }

//     ul.icons li {
//         display: inline-block;
//         padding: 0 1em 0 0;
//     }

//     ul.icons li:last-child {
//         padding-right: 0;
//     }

//     ul.icons li .icon:before {
//         font-size: 2em;
//     }

//     ul.actions {
//         cursor: default;
//         list-style: none;
//         padding-left: 0;
//     }

//     ul.actions li {
//         display: inline-block;
//         padding: 0 1em 0 0;
//         vertical-align: middle;
//     }

//     ul.actions li:last-child {
//         padding-right: 0;
//     }

//     ul.actions.small li {
//         padding: 0 0.5em 0 0;
//     }

//     ul.actions.vertical li {
//         display: block;
//         padding: 1em 0 0 0;
//     }

//     ul.actions.vertical li:first-child {
//         padding-top: 0;
//     }

//     ul.actions.vertical li > * {
//         margin-bottom: 0;
//     }

//     ul.actions.vertical.small li {
//         padding: 0.5em 0 0 0;
//     }

//     ul.actions.vertical.small li:first-child {
//         padding-top: 0;
//     }

//     ul.actions.fit {
//         display: table;
//         margin-left: -1em;
//         padding: 0;
//         table-layout: fixed;
//         width: calc(100% + 1em);
//     }

//     ul.actions.fit li {
//         display: table-cell;
//         padding: 0 0 0 1em;
//     }

//     ul.actions.fit li > * {
//         margin-bottom: 0;
//     }

//     ul.actions.fit.small {
//         margin-left: -0.5em;
//         width: calc(100% + 0.5em);
//     }

//     ul.actions.fit.small li {
//         padding: 0 0 0 0.5em;
//     }

//     dl {
//         margin: 0 0 2em 0;
//     }

//     dl dt {
//         display: block;
//         font-weight: 700;
//         margin: 0 0 1em 0;
//     }

//     dl dd {
//         margin-left: 2em;
//     }

//     ul.alt li {
//         border-top-color: #e5474b;
//     }
// }

// // Section/Article
// :root {
//     section.special,
//     article.special {
//         text-align: center;
//     }

//     section .inner {
//         max-width: 65em;
//         width: calc(100% - 6em);
//         margin: 0 auto;
//     }

//     @media screen and (max-width: 480px) {
//         section .inner {
//             max-width: 90%;
//             width: 90%;
//         }
//     }

//     header p {
//         position: relative;
//         margin: 0 0 1.5em 0;
//     }

//     header h2 + p {
//         font-size: 1.25em;
//         margin-top: -1em;
//     }

//     header h3 + p {
//         font-size: 1.1em;
//         margin-top: -0.8em;
//     }

//     header h4 + p,
//     header h5 + p,
//     header h6 + p {
//         font-size: 0.9em;
//         margin-top: -0.6em;
//     }

//     header p {
//         color: #717171;
//     }
// }

// // Banner
// :root {
//     #banner {
//         background-color: #e5474b;
//         color: #f2a3a5;
//         padding: 13em 0 11em 0;
//         background-color: #0c0c0c;
//         background-image: url("../images/banner.jpg");
//         background-size: cover;
//         background-repeat: no-repeat;
//         background-position: 15% left;
//         text-align: left;
//         position: relative;
//         z-index: 9999;
//     }

//     #banner input,
//     #banner select,
//     #banner textarea {
//         color: #ffffff;
//     }

//     #banner a {
//         color: #ffffff;
//     }

//     #banner strong,
//     #banner b {
//         color: #ffffff;
//     }

//     #banner h1,
//     #banner h2,
//     #banner h3,
//     #banner h4,
//     #banner h5,
//     #banner h6 {
//         color: #fff;
//     }

//     #banner blockquote {
//         border-left-color: #fff;
//     }

//     #banner code {
//         background: none;
//         border-color: #fff;
//     }

//     #banner hr {
//         border-bottom-color: #fff;
//     }

//     #banner input[type="submit"],
//     #banner input[type="reset"],
//     #banner input[type="button"],
//     #banner button,
//     #banner .button {
//         background-color: #5a5a5a;
//         color: #ffffff !important;
//     }

//     #banner input[type="submit"]:hover,
//     #banner input[type="reset"]:hover,
//     #banner input[type="button"]:hover,
//     #banner button:hover,
//     #banner .button:hover {
//         background-color: #676767;
//     }

//     #banner input[type="submit"]:active,
//     #banner input[type="reset"]:active,
//     #banner input[type="button"]:active,
//     #banner button:active,
//     #banner .button:active {
//         background-color: #4d4d4d;
//     }

//     #banner input[type="submit"].alt,
//     #banner input[type="reset"].alt,
//     #banner input[type="button"].alt,
//     #banner button.alt,
//     #banner .button.alt {
//         background-color: transparent;
//         box-shadow: inset 0 0 0 2px #fff;
//         color: #ffffff !important;
//     }

//     #banner input[type="submit"].alt:hover,
//     #banner input[type="reset"].alt:hover,
//     #banner input[type="button"].alt:hover,
//     #banner button.alt:hover,
//     #banner .button.alt:hover {
//         background: rgba(255, 255, 255, 0.25);
//     }

//     #banner input[type="submit"].alt:active,
//     #banner input[type="reset"].alt:active,
//     #banner input[type="button"].alt:active,
//     #banner button.alt:active,
//     #banner .button.alt:active {
//         background-color: rgba(255, 255, 255, 0.2);
//     }

//     #banner input[type="submit"].alt.icon:before,
//     #banner input[type="reset"].alt.icon:before,
//     #banner input[type="button"].alt.icon:before,
//     #banner button.alt.icon:before,
//     #banner .button.alt.icon:before {
//         color: #f8d1d2;
//     }

//     #banner input[type="submit"].special,
//     #banner input[type="reset"].special,
//     #banner input[type="button"].special,
//     #banner button.special,
//     #banner .button.special {
//         background-color: #ffffff;
//         color: #e5474b !important;
//     }

//     #banner:after {
//         -moz-transition: opacity 4s ease;
//         -webkit-transition: opacity 4s ease;
//         -ms-transition: opacity 4s ease;
//         transition: opacity 4s ease;
//         content: "";
//         position: absolute;
//         width: 100%;
//         height: 100%;
//         display: block;
//         top: 0;
//         left: 0;
//         background-color: #0c0c0c;
//         opacity: 0.25;
//     }

//     #banner .inner {
//         max-width: 65em;
//         width: calc(100% - 6em);
//         margin: 0 auto;
//         position: relative;
//         z-index: 10000;
//         line-height: 1.5;
//     }

//     @media screen and (max-width: 480px) {
//         #banner .inner {
//             max-width: 90%;
//             width: 90%;
//         }
//     }

//     #banner h1 {
//         font-size: 2em;
//         margin: 0 0 1em 0;
//         padding: 0;
//         letter-spacing: 3px;
//         font-weight: 700;
//     }

//     #banner h1 span {
//         font-weight: 400;
//     }

//     body.is-loading #banner:after {
//         opacity: 1;
//     }

//     @media screen and (max-width: 1680px) {
//         #banner {
//             padding: 10em 0 8em 0;
//         }
//     }

//     @media screen and (max-width: 1280px) {
//         #banner {
//             padding: 8em 0 6em 0;
//         }
//     }

//     @media screen and (max-width: 980px) {
//         #banner {
//             padding: 12em 0 10em 0;
//         }

//         #banner br {
//             display: none;
//         }
//     }

//     @media screen and (max-width: 736px) {
//         #banner {
//             padding: 4em 0 2em 0;
//         }

//         #banner h1 {
//             font-size: 1.75em;
//         }
//     }

//     @media screen and (max-width: 480px) {
//         #banner {
//             padding: 5em 0 3em 0;
//         }

//         #banner ul {
//             margin-top: 1em;
//         }
//     }
// }

// // Main
// :root {
//     #main {
//         padding: 4em 0 2em 0;
//     }

//     #one {
//         padding: 6em 0 4em 0;
//     }

//     @media screen and (max-width: 980px) {
//         #one {
//             padding: 4em 0 2em 0;
//         }
//     }

//     @media screen and (max-width: 736px) {
//         #one {
//             padding: 2em 0 0.1em 0;
//         }
//     }

//     #two {
//         padding: 6em 0 4em 0;
//         background: #f3f3f3;
//         background: -moz-linear-gradient(left, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
//         background: -webkit-linear-gradient(left, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
//         background: linear-gradient(to right, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
//         filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f3f3f3', endColorstr='#f7f7f7',GradientType=1 );
//     }

//     #two .inner {
//         display: -ms-flexbox;
//         display: -moz-flex;
//         display: -webkit-flex;
//         display: -ms-flex;
//         display: flex;
//         -moz-flex-direction: row;
//         -webkit-flex-direction: row;
//         -ms-flex-direction: row;
//         flex-direction: row;
//     }

//     #two .inner article {
//         width: 50%;
//     }

//     #two .inner article:first-child {
//         padding-right: 6em;
//     }

//     #two .inner article:last-child {
//         padding-left: 6em;
//     }

//     @media screen and (max-width: 980px) {
//         #two {
//             padding: 4em 0 2em 0;
//             background: -moz-linear-gradient(top, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
//             background: -webkit-linear-gradient(top, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
//             background: linear-gradient(to bottom, #f3f3f3 0%, #f3f3f3 50%, #f7f7f7 0%, #f7f7f7 100%);
//             filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f3f3f3', endColorstr='#f7f7f7',GradientType=0 );
//         }

//         #two .inner {
//             -moz-flex-direction: column;
//             -webkit-flex-direction: column;
//             -ms-flex-direction: column;
//             flex-direction: column;
//         }

//         #two .inner article {
//             width: 100%;
//         }

//         #two .inner article:first-child {
//             padding-right: 0;
//             padding-bottom: 2em;
//         }

//         #two .inner article:last-child {
//             padding-left: 0;
//             padding-top: 2em;
//         }
//     }

//     @media screen and (max-width: 736px) {
//         #two {
//             padding: 2em 0 0.1em 0;
//         }
//     }

//     #three {
//         padding: 6em 0 4em 0;
//     }

//     #three .inner {
//         display: -ms-flexbox;
//         display: -moz-flex;
//         display: -webkit-flex;
//         display: -ms-flex;
//         display: flex;
//         -moz-flex-direction: row;
//         -webkit-flex-direction: row;
//         -ms-flex-direction: row;
//         flex-direction: row;
//         -moz-justify-content: space-between;
//         -webkit-justify-content: space-between;
//         -ms-justify-content: space-between;
//         justify-content: space-between;
//         -ms-flex-pack: justify;
//     }

//     #three .inner article {
//         width: 26%;
//         display: block;
//     }

//     #three .inner article p {
//         color: #717171;
//     }

//     #three .inner article .icon {
//         color: #b3b3b3;
//         font-size: 3em;
//     }

//     @media screen and (max-width: 980px) {
//         #three .inner {
//             -moz-flex-direction: column;
//             -webkit-flex-direction: column;
//             -ms-flex-direction: column;
//             flex-direction: column;
//         }

//         #three .inner article {
//             width: 100%;
//             margin: 0 auto;
//         }
//     }

//     @media screen and (max-width: 980px) {
//         #three {
//             padding: 4em 0 2em 0;
//         }
//     }

//     @media screen and (max-width: 736px) {
//         #three {
//             padding: 2em 0 0.1em 0;
//         }
//     }
// }
</style>