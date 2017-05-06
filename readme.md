# prepend-http [![Build Status](https://travis-ci.org/sindresorhus/prepend-http.svg?branch=master)](https://travis-ci.org/sindresorhus/prepend-http)

[![Greenkeeper badge](https://badges.greenkeeper.io/blakeembrey/prepend-http.svg)](https://greenkeeper.io/)

> Prepend `http://` to humanized URLs like `todomvc.com` and `localhost`


## Install

```sh
$ npm install --save prepend-http
```


## Usage

```js
var prependHttp = require('prepend-http');

prependHttp('todomvc.com');
//=> http://todomvc.com

prependHttp('localhost');
//=> http://localhost

prependHttp('http://todomvc.com');
//=> http://todomvc.com
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
