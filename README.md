# [gulp][gulp]-cssnano [![Build Status](https://travis-ci.org/ben-eb/gulp-cssnano.svg?branch=master)][ci] [![NPM version](https://badge.fury.io/js/gulp-cssnano.svg)][npm] [![Dependency Status](https://gemnasium.com/ben-eb/gulp-cssnano.svg)][deps]

> Minify CSS with cssnano.

## Install

With [npm](https://npmjs.org/package/gulp-cssnano) do:

```
npm install gulp-cssnano --save-dev
```

## Example

```js
var gulp = require('gulp');
var nano = require('gulp-cssnano');

gulp.task('default', function() {
    return gulp.src('./main.css')
        .pipe(nano())
        .pipe(gulp.dest('./out'));
});
```

## Contributing

Pull requests are welcome. If you add functionality, then please add unit tests
to cover it.

## License

MIT © [Ben Briggs](http://beneb.info)

[ci]:      https://travis-ci.org/ben-eb/gulp-cssnano
[deps]:    https://gemnasium.com/ben-eb/gulp-cssnano
[npm]:     http://badge.fury.io/js/gulp-cssnano
