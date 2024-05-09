# @diotoborg/distinctio-voluptates-deleniti <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@diotoborg/distinctio-voluptates-deleniti');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/distinctio-voluptates-deleniti
[npm-version-svg]: https://versionbadg.es/inspect-js/@diotoborg/distinctio-voluptates-deleniti.svg
[deps-svg]: https://david-dm.org/inspect-js/@diotoborg/distinctio-voluptates-deleniti.svg
[deps-url]: https://david-dm.org/inspect-js/@diotoborg/distinctio-voluptates-deleniti
[dev-deps-svg]: https://david-dm.org/inspect-js/@diotoborg/distinctio-voluptates-deleniti/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@diotoborg/distinctio-voluptates-deleniti#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/distinctio-voluptates-deleniti.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/distinctio-voluptates-deleniti.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/distinctio-voluptates-deleniti.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/distinctio-voluptates-deleniti
[codecov-image]: https://codecov.io/gh/inspect-js/@diotoborg/distinctio-voluptates-deleniti/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@diotoborg/distinctio-voluptates-deleniti/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@diotoborg/distinctio-voluptates-deleniti
[actions-url]: https://github.com/diotoborg/distinctio-voluptates-deleniti/actions
