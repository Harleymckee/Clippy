[Clippy](http://bennettfeely.com/clippy)
======

Shape up your website with CSS clip-paths.

Clippy is a tool for generating values for shape functions with the CSS clip-path property. The property accepts several basic shapes that will be able to create with Clippy and their current implementation status:

* `circle()` Buggy, does not work without a 1:1 size ratio.
* `ellipse()` Done.
* `polygon()` Done.
* `inset()` Done, looking into how to support `radius` value.


#### Details
* Utilizes [draggabilly.js](https://github.com/desandro/draggabilly) for the handles which each correspond to a point for CSS clip path. Works really well on touch devices, especially with the `touch-action: none`.
* Using Grunt with SCSS, autoprefixer, uncss, minification for CSS, HTML, and soon, jQuery and images.
* Material design-ish inspiration.
* Mobile-first design, making things work great on mobile touch devices and will work responsively upwards from there.


#### To do

* Make a panel card with quick information about the `clip-path` property.
* Add HTML5 localstorage to save things.
* See how Clippy could be used with [CSS Shapes module](http://dev.w3.org/csswg/css-shapes/#basic-shape-functions).

***

#### Browser Support

[caniuse.com](http://caniuse.com/#search=clip-path)
