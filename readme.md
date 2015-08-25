# gulp-ast-support [![Build Status](https://travis-ci.org/jamestalmage/gulp-ast-support.svg?branch=master)](https://travis-ci.org/jamestalmage/gulp-ast-support)

> My great gulp plugin


## Install

```
$ npm install --save-dev gulp-ast-support
```


## Usage

```js
var gulp = require('gulp');
var astSupport = require('gulp-ast-support');

gulp.task('default', function () {
	return gulp.src('src/file.ext')
		.pipe(astSupport())
		.pipe(gulp.dest('dist'));
});
```


## API

### astSupport(options)

#### options

##### foo

Type: `boolean`  
Default: `false`

Lorem ipsum.


## License

MIT © [James Talmage](http://github.com/jamestalmage)
