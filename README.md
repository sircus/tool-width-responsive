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
<div class="t-[sm|md|lg]-width[1-10]of[2-10]"></div>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
