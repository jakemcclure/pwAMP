# pwAMP

[![license][license-image]][license-url] [![Build Status][travis-image]][travis-url]
> AMP + PWA, putting it all together

## Prerequisites

To install this project, you'll need the following things installed on your machine.

- [x] [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
- [x] [NodeJS](http://nodejs.org) - use the installer.
- [x] NPM

## Local Installation

- [x] Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**Development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc.

```shell
$ npm run gulp
```

**Deploy mode**

You can easily deploy your site build with the command
```shell
$ npm run gulp deploy
```

## Tests

If you want to run the tests on your local machine please install `gem install html-proofer`. And then run the tests using
```shell
$ htmlproofer ./_site
```

[license-image]: https://img.shields.io/badge/license-ISC-blue.svg
[license-url]: https://github.com/jakemcclure/pwAMP/blob/master/LICENSE
[travis-image]: https://travis-ci.org/jakemcclure/pwAMP.svg?branch=master
[travis-url]: https://travis-ci.org/jakemcclure/pwAMP
