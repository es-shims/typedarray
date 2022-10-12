# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v0.0.6](https://github.com/ljharb/typedarray/compare/v0.0.5...v0.0.6) - 2014-05-17

### Commits

- link to browserify cdn [`f5be9e4`](https://github.com/ljharb/typedarray/commit/f5be9e4263964f9d711e42d0f5f0bd40b9e38cf8)
- upgrade tape [`56bd728`](https://github.com/ljharb/typedarray/commit/56bd728e1891a0501de8a7deb181641a51050c0d)

## [v0.0.5](https://github.com/ljharb/typedarray/compare/v0.0.4...v0.0.5) - 2013-12-12

### Commits

- Ensure defineProp is always defined [`316be36`](https://github.com/ljharb/typedarray/commit/316be36ac631521ccbf00a9557a2dda0c3e5b17e)

## [v0.0.4](https://github.com/ljharb/typedarray/compare/v0.0.3...v0.0.4) - 2013-12-10

### Commits

- Remove "reserved words" variable names (for IE6-8) [`60869cc`](https://github.com/ljharb/typedarray/commit/60869cc3f8c32fe43dc912a9f9e186d0545e425c)

## [v0.0.3](https://github.com/ljharb/typedarray/compare/v0.0.2...v0.0.3) - 2013-12-10

### Commits

- Fix more ReferenceError bugs in DataView [`ddb968a`](https://github.com/ljharb/typedarray/commit/ddb968af2d186b57d4e59371d232df435ac56004)

## [v0.0.2](https://github.com/ljharb/typedarray/compare/v0.0.1...v0.0.2) - 2013-12-10

### Commits

- Fix "ReferenceError: 'ArrayBuffer' is undefined" when initializing a DataView [`1ffacbc`](https://github.com/ljharb/typedarray/commit/1ffacbcef06f1c9d699242cb7a1f65d32b101ee5)

## [v0.0.1](https://github.com/ljharb/typedarray/compare/v0.0.0...v0.0.1) - 2013-12-10

### Fixed

- 0.0.1 [`#1`](https://github.com/ljharb/typedarray/issues/1)

### Commits

- removing `.` in error message [`62210c3`](https://github.com/ljharb/typedarray/commit/62210c32f4f946652f3acede6a60023c4259fab2)
- test ie6+ [`f041445`](https://github.com/ljharb/typedarray/commit/f041445bf8d45b8024ca2fcd2b31e19c15240579)

## v0.0.0 - 2013-12-09

### Commits

- remove use of `global` [`a72dae8`](https://github.com/ljharb/typedarray/commit/a72dae8f5f5b1e3379a1ca357c0858201766730d)
- initial code ripped from https://raw.github.com/inexorabletash/polyfill/master/typedarray.js [`1b9b2c1`](https://github.com/ljharb/typedarray/commit/1b9b2c173d23345fc9d944b1ef6de9f91d677420)
- examples, readme, package.json [`9d1f718`](https://github.com/ljharb/typedarray/commit/9d1f71824a6edbc6e6763da9c5d74837f32acd1b)
- get rid of global setting of object function shims for defineProperty and getOwnPropertyNames [`33d79b8`](https://github.com/ljharb/typedarray/commit/33d79b8342e7c185183f17fe95cb2508fb43701a)
- explicit global references, undef_globals test passes [`621d039`](https://github.com/ljharb/typedarray/commit/621d039595265d46dd2575d9ccbcf15a04d2b978)
- testling, travis [`424dc38`](https://github.com/ljharb/typedarray/commit/424dc389295d9db5a06488695c0df598f8c75c0e)
- failing test since `global` assignment in index relies on global for scoping [`05be36a`](https://github.com/ljharb/typedarray/commit/05be36afd4197cddbc4387506690107aee43b2c9)
- tiny passing uint8array test [`6b2f8f1`](https://github.com/ljharb/typedarray/commit/6b2f8f12c99d35f2a88080ddfa8ddea3d60cbd6f)
