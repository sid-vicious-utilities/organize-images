# ncmd

This is a simple implementation of file management. The the current command will recursively search files from a source directory and copy the file to a destination directory organized by folders based on date created field.

[![downloads][downloads-image]][downloads-url]
[![npm][npm-image]][npm-url]
[![NPM version][npm-v-image]][npm-url]
[![travis][travis-image]][travis-url]
[![Code Climate][codeclimate-image]][codeclimate-url]
[![Codacy Badge][codacy-image]][codacy-url]

## Installation

    $ npm install ncmd -g

## Usage
  
  Usage: index [options]

  Options:

    -h, --help                output usage information
    -V, --version             output the version number
    -S, --source <path>       source directory of the images
    -D, --destination <path>  destination directory of the organized images
    -v, --verbose             verbose mode

## License

  Apache-2.0

[travis-image]: https://travis-ci.org/slahiri/ncmd.svg?branch=master
[travis-url]: https://travis-ci.org/slahiri/ncmd
[npm-image]: https://img.shields.io/npm/l/ncmd.svg
[npm-v-image]: https://img.shields.io/npm/v/gulp.svg
[npm-url]: https://www.npmjs.com/package/ncmd
[downloads-image]: https://img.shields.io/npm/dt/ncmd.svg
[downloads-url]: https://www.npmjs.com/package/ncmd
[codeclimate-image]: https://codeclimate.com/github/slahiri/ncmd/badges/gpa.svg
[codeclimate-url]: https://codeclimate.com/github/slahiri/ncmd
[codacy-image]: https://api.codacy.com/project/badge/grade/d4a372fb631e48a69d290169660543b8
[codacy-url]: https://www.codacy.com/app/siddhartha-lahiri/ncmd