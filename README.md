<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Black Cañon

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> [Image][@osullivan:1871a] of Black Canyon.

<section class="intro">

[Image][@osullivan:1871a] of Timothy H. O'Sullivan's albumen silver print _Black Cañon, Colorado River, From Camp 8, Looking Above_.

<!-- <image align="center" src="./data/image.jpg" alt="Black Canyon"> -->

<div class="image" align="center">
    <img src="https://cdn.rawgit.com/stdlib-js/stdlib/1d23896443c65382340a9b4dfb5adc7764f8d23b/lib/node_modules/@stdlib/datasets/img-black-canyon/data/image.jpg" alt="Black Canyon">
    <br>
</div>

<!-- </image> -->

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/datasets-img-black-canyon
```

</section>

<section class="usage">

## Usage

```javascript
var image = require( '@stdlib/datasets-img-black-canyon' );
```

#### image()

Returns a [buffer][@stdlib/buffer/ctor] containing image data.

```javascript
var img = image();
// returns <Buffer>
```

</section>

<!-- /.usage -->

<section class="examples">

<!-- TODO: more creative example. -->

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var image = require( '@stdlib/datasets-img-black-canyon' );

var img = image();
console.log( img );
```

</section>

<!-- /.examples -->

* * *

<section class="cli">

## CLI

<section class="installation">

## Installation

To use the module as a general utility, install the module globally

```bash
npm install -g @stdlib/datasets-img-black-canyon
```

</section>

<section class="usage">

### Usage

```text
Usage: img-black-canyon [options]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->

<section class="examples">

### Examples

```bash
$ img-black-canyon | <image_viewer>
```

</section>

<!-- /.examples -->

</section>

<!-- /.cli -->

<!-- <license> -->

## License

Digital image courtesy of the Getty's [Open Content Program][getty-open-content]. The data files (databases) are licensed under an [Open Data Commons Public Domain Dedication & License 1.0][pddl-1.0] and their contents are licensed under [Creative Commons Zero v1.0 Universal][cc0]. The software is licensed under [Apache License, Version 2.0][apache-license].

<!-- </license> -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-img-black-canyon.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-img-black-canyon

[test-image]: https://github.com/stdlib-js/datasets-img-black-canyon/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/datasets-img-black-canyon/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-img-black-canyon/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-img-black-canyon?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-img-black-canyon
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-img-black-canyon/main

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/datasets-img-black-canyon/main/LICENSE

[getty-open-content]: http://www.getty.edu/about/opencontent.html

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[@osullivan:1871a]: http://www.getty.edu/art/collection/objects/40209/timothy-h-o'sullivan-black-canon-colorado-river-from-camp-8-looking-above-american-1871/

[@stdlib/buffer/ctor]: https://github.com/stdlib-js/buffer-ctor

</section>

<!-- /.links -->
