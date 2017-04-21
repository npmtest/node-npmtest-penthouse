# npmtest-penthouse

#### basic test coverage for  [penthouse (v0.10.9)](https://github.com/pocketjoso/penthouse)  [![npm package](https://img.shields.io/npm/v/npmtest-penthouse.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-penthouse) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-penthouse.svg)](https://travis-ci.org/npmtest/node-npmtest-penthouse)

#### Generate critical path CSS for web pages

[![NPM](https://nodei.co/npm/penthouse.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/penthouse)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-penthouse/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-penthouse/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-penthouse/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-penthouse/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-penthouse/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-penthouse/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-penthouse/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-penthouse/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-penthouse/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-penthouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-penthouse/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-penthouse/build/test-report.html](https://npmtest.github.io/node-npmtest-penthouse/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-penthouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-penthouse/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-penthouse/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-penthouse/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-penthouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-penthouse/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-penthouse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-penthouse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonas Ohlsson",
        "url": "https://jonassebastianohlsson.com"
    },
    "bugs": {
        "url": "https://github.com/pocketjoso/penthouse/issues"
    },
    "contributors": [
        {
            "name": "Jonas Ohlsson",
            "url": "http://jonassebastianohlsson.com"
        },
        {
            "name": "Carl-Erik Kopseng",
            "url": "http://github.com/fatso83"
        }
    ],
    "dependencies": {
        "apartment": "^1.1.1",
        "css": "git+https://github.com/pocketjoso/css.git",
        "css-mediaquery": "^0.1.2",
        "jsesc": "^1.0.0",
        "os-tmpdir": "^1.0.1",
        "phantomjs-prebuilt": "^2.1.3",
        "tmp": "0.0.31"
    },
    "description": "Generate critical path CSS for web pages",
    "devDependencies": {
        "babel-core": "^6.8.0",
        "babel-preset-es2015": "^6.6.0",
        "chai": "^1.9.1",
        "css-compare-screenshots": "0.0.7",
        "global-mocha": "^1.0.1",
        "gm": "^1.21.1",
        "jshint": "^2.9.3",
        "mocha": "^1.20.1",
        "rimraf": "^2.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "e3fbc08af86daf38312e7230ab4c1d43d238e554",
        "tarball": "https://registry.npmjs.org/penthouse/-/penthouse-0.10.9.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "files": [
        "lib/**/*.js",
        "lib/phantomjs/config.json"
    ],
    "gitHead": "5e8cfb921fa5f65b3aa0c1b25eb91fe218200764",
    "homepage": "https://github.com/pocketjoso/penthouse",
    "keywords": [
        "CSS Critical Path Generator",
        "phantomjs",
        "css",
        "performance",
        "build",
        "tool"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "fatso83"
        },
        {
            "name": "pocketjoso"
        }
    ],
    "name": "penthouse",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/pocketjoso/penthouse.git#master"
    },
    "scripts": {
        "lint": "jshint .",
        "test": "npm run lint && mocha --compilers js:babel-core/register test/core-tests.js",
        "test-all": "npm run lint && mocha --compilers js:babel-core/register"
    },
    "version": "0.10.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
