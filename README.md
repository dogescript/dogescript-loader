# dogescript-loader

[![Build Status](https://secure.travis-ci.org/dogescript/dogescript-loader.svg?branch=master)](http://travis-ci.org/dogescript/dogescript-loader) [![Dependency Status](https://gemnasium.com/dogescript/dogescript-loader.svg)](https://gemnasium.com/dogescript/dogescript-loader) [![NPM version](https://badge.fury.io/js/dogescript-loader.svg)](http://badge.fury.io/js/dogescript-loader)

> Bundle [dogescript](https://github.com/dogescript/dogescript) files in [webpack](https://github.com/webpack/webpack)

![wow](https://raw.github.com/dogescript/dogescript-loader/master/media/doge-01.jpg)

## Usage

First the loader to the [webpack config](https://webpack.github.io/docs/configuration.html):

```js
module: {
  loaders: [
    { test: /\.djs$/, loader: 'dogescript-loader' }
  ]
}
```

Then require dogescript from plain JavaScript:

```js
var doge = require('./lib/doge.djs');

var wow = doge.amaze();
```


Or even better, require dogescript from dogescript:

```djs
so doge.djs as doge

very wow is plz doge.amaze
```
 
For the same in serverside node.js see [require-doge](https://github.com/dogescript/require-doge).

## Install

````
npm install dogescript-loader --save-dev
````


## History

* 0.1.3 - Moved to dogescript org
* 0.1.2 - Fix doge
* 0.1.0 - Top doge


## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.


## License

Copyright (c) 2014 [Bart van der Schoor](https://github.com/Bartvds)

Licensed under the MIT license.
