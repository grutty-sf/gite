# gits

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/gits.svg?style=flat-square
[npm-url]: https://npmjs.org/package/gits
[travis-image]: https://img.shields.io/travis/eggjs/gits.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/gits
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/gits.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/gits?branch=master
[david-image]: https://img.shields.io/david/eggjs/gits.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/gits
[snyk-image]: https://snyk.io/test/npm/gits/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/gits
[download-image]: https://img.shields.io/npm/dm/gits.svg?style=flat-square
[download-url]: https://npmjs.org/package/gits

<!--
Description here.
-->

## Install

```bash
$ npm i gite -g --save
```

## Usage
> First you have to set config.js

$ gite pull --groupProjectName
$ gite pull --groupProjectName=all
$ gite pull --groupProjectName=projectName

## Configuration

```js
// {app_root}/config.js
module.exports = {
    groupProjectName: {
        path: groupPath
        development: [], //[project1, project2]
        projects: [] //all project
     }
};
```

## Example
First you have to set config.js
$ gite branch --groupProjectName

## License

[MIT](LICENSE)
