<template>
    <section id="one">
		<div class="inner">
		    <header>
				<h2>Magna Etiam Lorem</h2>
			</header>
				<p>Suspendisse mauris. Fusce accumsan mollis eros. Pellentesque a diam sit amet mi ullamcorper vehicula. Integer adipiscin sem. Nullam quis massa sit amet nibh viverra malesuada. Nunc sem lacus, accumsan quis, faucibus non, congue vel, arcu, erisque hendrerit tellus. Integer sagittis. Vivamus a mauris eget arcu gravida tristique. Nunc iaculis mi in ante.</p>
					<ul class="actions">
						<li><a href="#" class="button alt">Learn More</a></li>
		</ul>
                    
		</div>
	</section>
</template>

<style>
h2 {
    padding: 0;
    border: 0;
    vertical-align: baseline;
    font-weight: 700;
    line-height: 1.5;
    margin: 0 0 35px 0;
    text-transform: uppercase;
    text-decoration: none;
    font-size: 1.75em;
    color: #e5474b;
}
#one {
    padding: 6em 0 4em 0;
    margin: 0px;
    font-size: 15pt;
    font-weight: 300;
    line-height: 2;
    font-family: "Lato", sans-serif;
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
@media screen and (max-width: 480px) {
    #one {
        font-size: 12pt;
    }
}
@media screen and (max-width: 980px) {
    #one {
        font-size: 12pt;
    }
}
@media screen and (max-width: 1280px) {
    #one {
        font-size: 13pt;
    }
}
@media screen and (max-width: 1680px) {
    #one {
        font-size: 13pt;
    }
}
section {
    vertical-align: baseline;
}

section .inner {
    max-width: 65em;
    width: calc(100% - 6em);
    margin: 0 auto;
    text-align: left;
}

@media screen and (max-width: 480px) {
    section .inner {
        max-width: 90%;
        width: 90%;
    }
}
header,
p {
    margin: 0 0 2em 0;
    color: #111111;
}
ul {
    padding-left: 0;
    margin: 0 0 2em 0;
    font-family: "Lato", sans-serif;

    list-style: none;
}
li {
    padding: 0 1em 0 0;
}

.button.alt {
    background-color: transparent;
    box-shadow: inset 0 0 0 2px #e5474b;
    color: #e5474b !important;
    display: inline-block;
    font-size: 0.8em;
    font-weight: 700;
    height: 3.5em;
    line-height: 3.65em;
    padding: 0 2.25em;
    text-align: center;
    text-decoration: none;
    text-transform: uppercase;
    font-family: "Lato", sans-serif;
}
.button.alt:hover {
    background: #fceced;
}
</style>
