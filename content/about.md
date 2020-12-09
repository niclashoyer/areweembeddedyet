+++
title = "About AWEY"
+++

## About

Are We Embedded Yet – or AWEY for short – tries to answer the question: **Can I use Rust to do embedded development (yet)?**

## How to use the site

This website has various features that make your life easier researching whether you can use Rust for the embedded development already or not. While some stuff is possible already, other parts are still challenging and this website wants to give you insight for your particular case. The easiest is to start looking into the [topics](/topics/) most relevant for you.

While most things should be rather quick to comprehend, there are some features, we'd like to explain to you a little deeper to improve the speed with which you can answer the question for you.

### The Package Info

![Package Info](/about/package-info.png)

For each package we list the most important information in one quick view. Aside from the package id (`embedded-hal`), the header shows various links – if available: the crate.io-page, the homepage, the documentation and to the source code. Tip: When you hover over name, it also shows when the package was created and last updated.

In the second row features the latest published version number, how often the package has been downloaded so far and how it is licensed – all as pretty badges of live data pulled from [shields.io](http://shields.io/).

Under that you can find the short description provided for that package.

### Understanding the level indicator

Throughout the app – mostly on section titles – you find the small `level indicators`: a colored glyph, which should give you a hint on the maturity of the subject overall as designated by the [curators](/curators/). The following indicators are available:

<ul>
  <li>{{ level(level=0) }} – everything is awesome<a href="https://www.youtube.com/watch?v=9cQgQIMlwWw" target="_blank">™</a>: stable, tested and mature</li>
  <li>{{ level(level=1) }} – stuff's pretty great</li>
  <li>{{ level(level=2) }} – getting there, stable but still maturing</li>
  <li>{{ level(level=3) }} – not yet stable, but progressing</li>
  <li>{{ level(level=4) }} – unstable/incomplete, needs work</li>
  <li>{{ level(level=5) }} – barely there, needs serious work</li>
  <li>{{ level(level=6) }} – basically non-existent</li>
</ul>

If you need a reminder, you can also just hover over the glyph to get the text.


## Credits

This project stands on giant shoulders, as it was forked from the awesome [`arewewebyet`](https://github.com/rust-lang/arewewebyet) and tries to follow its development. In the future we might diverge more as we see fit.

The content is curated by the [curators](/curators/). All content is licensed under the [Creative Commons Attribution License (International)](https://github.com/bashyHQ/arewewebyet/blob/gh-pages/LICENSE).
