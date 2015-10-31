# gulp-htmlmin [![NPM version](https://badge.fury.io/js/gulp-htmlmin.svg)](http://badge.fury.io/js/gulp-htmlmin)  [![Build Status](https://travis-ci.org/jonschlinkert/gulp-htmlmin.svg)](https://travis-ci.org/jonschlinkert/gulp-htmlmin)

> gulp plugin to minify HTML.

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i gulp-htmlmin --save-dev
```

## Usage

```js
var gulp = require('gulp');
var htmlmin = require('gulp-htmlmin');

gulp.task('minify', function() {
  return gulp.src('src/*.html')
    .pipe(htmlmin({collapseWhitespace: true}))
    .pipe(gulp.dest('dist'))
});
```

See the [html-minifer docs](https://github.com/kangax/html-minifier) for options.

## Related projects

[gulp-prettify](https://www.npmjs.com/package/gulp-prettify): Prettify, format, beautify HTML. | [homepage](https://github.com/jonschlinkert/gulp-prettify)

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/expand-files/issues/new).

## Authors

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

**Shinnosuke Watanabe**

* [github/shinnn](https://github.com/shinnn)
* [twitter/shinnn_tw](http://twitter.com/shinnn_tw)

## License

Copyright © 2014-2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on October 31, 2015._