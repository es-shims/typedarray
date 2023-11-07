# typedarray <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

TypedArray polyfill ripped from [this module](https://github.com/inexorabletash/polyfill).

# example

``` js
var Uint8Array = require('typedarray').Uint8Array;
var ua = new Uint8Array(5);
ua[1] = 256 + 55;
console.log(ua[1]);
```

output:

```
55
```

# methods

``` js
var TA = require('typedarray')
```

The `TA` object has the following constructors:

* TA.ArrayBuffer
* TA.DataView
* TA.Float32Array
* TA.Float64Array
* TA.Int8Array
* TA.Int16Array
* TA.Int32Array
* TA.Uint8Array
* TA.Uint8ClampedArray
* TA.Uint16Array
* TA.Uint32Array

# install

With [npm](https://npmjs.org) do:

```
npm install typedarray
```

To use this module in the browser, compile with
[browserify](http://browserify.org)
or download a UMD build from browserify CDN:

http://wzrd.in/standalone/typedarray@latest

# License

MIT

Original can be found at:
  https://bitbucket.org/lindenlab/llsd
Modifications by Joshua Bell inexorabletash@gmail.com
  https://github.com/inexorabletash/polyfill

ES3/ES5 implementation of the Krhonos Typed Array Specification
  Ref: http://www.khronos.org/registry/typedarray/specs/latest/
  Date: 2011-02-01

Variations:
 * Allows `typed_array.get`/`set()` as alias for subscripts (`typed_array`[])

[package-url]: https://npmjs.org/package/typedarray
[npm-version-svg]: https://versionbadg.es/es-shims/typedarray.svg
[deps-svg]: https://david-dm.org/es-shims/typedarray.svg
[deps-url]: https://david-dm.org/es-shims/typedarray
[dev-deps-svg]: https://david-dm.org/es-shims/typedarray/dev-status.svg
[dev-deps-url]: https://david-dm.org/es-shims/typedarray#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/typedarray.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/typedarray.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/typedarray.svg
[downloads-url]: https://npm-stat.com/charts.html?package=typedarray
[codecov-image]: https://codecov.io/gh/es-shims/typedarray/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/es-shims/typedarray/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/es-shims/typedarray
[actions-url]: https://github.com/es-shims/typedarray/actions
