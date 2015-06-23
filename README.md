# sircus-tools-width-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-width-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-width-responsive)

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-width-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-width-responsive";
/*
@import "sircus-tools-width-responsive/lib/sm-width";
@import "sircus-tools-width-responsive/lib/md-width";
@import "sircus-tools-width-responsive/lib/lg-width";
*/
 @import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-width-responsive/converted";
// @import "./node_modules/sircus-tools-width-responsive/scss/sm-width";
// @import "./node_modules/sircus-tools-width-responsive/scss/md-width";
// @import "./node_modules/sircus-tools-width-responsive/scss/lg-width";
```


> html

```html
<!-- sm -->
<div class="t-sm-widthHalf"></div>
<div class="t-sm-widthFull"></div>

<div class="t-sm-width1of3"></div>
<div class="t-sm-width2of3"></div>

<div class="t-sm-width1of4"></div>
<div class="t-sm-width2of4"></div>
<div class="t-sm-width3of4"></div>

<div class="t-sm-width1of5"></div>
<div class="t-sm-width2of5"></div>
<div class="t-sm-width3of5"></div>
<div class="t-sm-width4of5"></div>

<div class="t-sm-width1of6"></div>
<div class="t-sm-width2of6"></div>
<div class="t-sm-width3of6"></div>
<div class="t-sm-width4of6"></div>
<div class="t-sm-width5of6"></div>

<div class="t-sm-width1of7"></div>
<div class="t-sm-width2of7"></div>
<div class="t-sm-width3of7"></div>
<div class="t-sm-width4of7"></div>
<div class="t-sm-width5of7"></div>
<div class="t-sm-width6of7"></div>

<div class="t-sm-width1of8"></div>
<div class="t-sm-width2of8"></div>
<div class="t-sm-width3of8"></div>
<div class="t-sm-width4of8"></div>
<div class="t-sm-width5of8"></div>
<div class="t-sm-width6of8"></div>
<div class="t-sm-width7of8"></div>

<div class="t-sm-width1of9"></div>
<div class="t-sm-width2of9"></div>
<div class="t-sm-width3of9"></div>
<div class="t-sm-width4of9"></div>
<div class="t-sm-width5of9"></div>
<div class="t-sm-width6of9"></div>
<div class="t-sm-width7of9"></div>
<div class="t-sm-width8of9"></div>

<div class="t-sm-width1of10"></div>
<div class="t-sm-width2of10"></div>
<div class="t-sm-width3of10"></div>
<div class="t-sm-width4of10"></div>
<div class="t-sm-width5of10"></div>
<div class="t-sm-width6of10"></div>
<div class="t-sm-width7of10"></div>
<div class="t-sm-width8of10"></div>
<div class="t-sm-width9of10"></div>


<!-- md -->
<div class="t-md-widthHalf"></div>
<div class="t-md-widthFull"></div>

<div class="t-md-width1of3"></div>
<div class="t-md-width2of3"></div>

<div class="t-md-width1of4"></div>
<div class="t-md-width2of4"></div>
<div class="t-md-width3of4"></div>

<div class="t-md-width1of5"></div>
<div class="t-md-width2of5"></div>
<div class="t-md-width3of5"></div>
<div class="t-md-width4of5"></div>

<div class="t-md-width1of6"></div>
<div class="t-md-width2of6"></div>
<div class="t-md-width3of6"></div>
<div class="t-md-width4of6"></div>
<div class="t-md-width5of6"></div>

<div class="t-md-width1of7"></div>
<div class="t-md-width2of7"></div>
<div class="t-md-width3of7"></div>
<div class="t-md-width4of7"></div>
<div class="t-md-width5of7"></div>
<div class="t-md-width6of7"></div>

<div class="t-md-width1of8"></div>
<div class="t-md-width2of8"></div>
<div class="t-md-width3of8"></div>
<div class="t-md-width4of8"></div>
<div class="t-md-width5of8"></div>
<div class="t-md-width6of8"></div>
<div class="t-md-width7of8"></div>

<div class="t-md-width1of9"></div>
<div class="t-md-width2of9"></div>
<div class="t-md-width3of9"></div>
<div class="t-md-width4of9"></div>
<div class="t-md-width5of9"></div>
<div class="t-md-width6of9"></div>
<div class="t-md-width7of9"></div>
<div class="t-md-width8of9"></div>

<div class="t-md-width1of10"></div>
<div class="t-md-width2of10"></div>
<div class="t-md-width3of10"></div>
<div class="t-md-width4of10"></div>
<div class="t-md-width5of10"></div>
<div class="t-md-width6of10"></div>
<div class="t-md-width7of10"></div>
<div class="t-md-width8of10"></div>
<div class="t-md-width9of10"></div>


<!-- lg -->
<div class="t-lg-widthHalf"></div>
<div class="t-lg-widthFull"></div>

<div class="t-lg-width1of3"></div>
<div class="t-lg-width2of3"></div>

<div class="t-lg-width1of4"></div>
<div class="t-lg-width2of4"></div>
<div class="t-lg-width3of4"></div>

<div class="t-lg-width1of5"></div>
<div class="t-lg-width2of5"></div>
<div class="t-lg-width3of5"></div>
<div class="t-lg-width4of5"></div>

<div class="t-lg-width1of6"></div>
<div class="t-lg-width2of6"></div>
<div class="t-lg-width3of6"></div>
<div class="t-lg-width4of6"></div>
<div class="t-lg-width5of6"></div>

<div class="t-lg-width1of7"></div>
<div class="t-lg-width2of7"></div>
<div class="t-lg-width3of7"></div>
<div class="t-lg-width4of7"></div>
<div class="t-lg-width5of7"></div>
<div class="t-lg-width6of7"></div>

<div class="t-lg-width1of8"></div>
<div class="t-lg-width2of8"></div>
<div class="t-lg-width3of8"></div>
<div class="t-lg-width4of8"></div>
<div class="t-lg-width5of8"></div>
<div class="t-lg-width6of8"></div>
<div class="t-lg-width7of8"></div>

<div class="t-lg-width1of9"></div>
<div class="t-lg-width2of9"></div>
<div class="t-lg-width3of9"></div>
<div class="t-lg-width4of9"></div>
<div class="t-lg-width5of9"></div>
<div class="t-lg-width6of9"></div>
<div class="t-lg-width7of9"></div>
<div class="t-lg-width8of9"></div>

<div class="t-lg-width1of10"></div>
<div class="t-lg-width2of10"></div>
<div class="t-lg-width3of10"></div>
<div class="t-lg-width4of10"></div>
<div class="t-lg-width5of10"></div>
<div class="t-lg-width6of10"></div>
<div class="t-lg-width7of10"></div>
<div class="t-lg-width8of10"></div>
<div class="t-lg-width9of10"></div>

```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
