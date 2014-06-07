# dogescript-loader

[![Build Status](https://secure.travis-ci.org/Bartvds/dogescript-loader.svg?branch=master)](http://travis-ci.org/Bartvds/dogescript-loader) [![Dependency Status](https://gemnasium.com/Bartvds/dogescript-loader.svg)](https://gemnasium.com/Bartvds/dogescript-loader) [![NPM version](https://badge.fury.io/js/dogescript-loader.svg)](http://badge.fury.io/js/dogescript-loader)

> Bundle [dogescript](https://github.com/remixz/dogescript) files in [webpack](https://github.com/webpack/webpack)

![wow](https://raw.github.com/Bartvds/dogescript-loader/master/media/doge-01.jpg)

## Usage

Add to the weebpack config:

```js
module: {
  loaders: [
    { test: /\.djs$/, loader: 'dogescript-loader' }
  ]
}
```

Use from plain JavaScript:

```js
var doge = require('./lib/doge.djs');

var wow = doge.amaze();
```


From dogescript:

```djs
so doge.djs as doge

var wow = doge.amaze();
```


## Install

````
npm install dogescript-loader --save-dev
````


## History

* 0.1.0 - Top doge


## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.


## License

Copyright (c) 2014 [Bart van der Schoor](https://github.com/Bartvds)

Licensed under the MIT license.
