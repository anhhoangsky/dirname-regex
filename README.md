# dirname-regex [![NPM version](https://badge.fury.io/js/dirname-regex.svg)](http://badge.fury.io/js/dirname-regex)

> Regular expression for matching the directory part of a file path.

## Install with [npm](npmjs.org)

```bash
npm i dirname-regex --save
```

## Usage

```js
var dirnameRe = require('dirname-regex');
var match = 'a/b/c/d.md'.match(dirnameRe());

match[0];
//=> 'a/b/c/d.md'

match[1];
//=> 'a/b/c/'

match[2];
//=> 'a/b/c'
```

See the [tests](./test.js) for more use cases and expected results.

## Run tests

Install dev dependencies:

```bash
node i -d && mocha
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/regexps/dirname-regex/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 


## License
Copyright (c) 2014-2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on January 12, 2015._
