# gulp-strip-css-comments [![Build Status](https://travis-ci.org/sindresorhus/gulp-strip-css-comments.svg?branch=master)](https://travis-ci.org/sindresorhus/gulp-strip-css-comments)

> Strip comments from CSS using [`strip-css-comments`](https://github.com/sindresorhus/strip-css-comments)


## Install

```sh
$ npm install --save-dev gulp-strip-css-comments
```


## Usage

```js
var gulp = require('gulp');
var stripCssComments = require('gulp-strip-css-comments');

gulp.task('default', function () {
	return gulp.src('src/app.css')
		.pipe(stripCssComments())
		.pipe(gulp.dest('dist'));
});
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
