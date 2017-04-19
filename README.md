# npmtest-curry

#### test coverage for  [curry (v1.2.0)](https://github.com/dominictarr/curry)  [![npm package](https://img.shields.io/npm/v/npmtest-curry.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-curry) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-curry.svg)](https://travis-ci.org/npmtest/node-npmtest-curry)

#### flexible but simple curry function

[![NPM](https://nodei.co/npm/curry.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/curry)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-curry/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-curry/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-curry/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-curry/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-curry/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-curry/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-curry/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-curry/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-curry/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-curry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-curry/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-curry/build/test-report.html](https://npmtest.github.io/node-npmtest-curry/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-curry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-curry/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-curry/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-curry/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-curry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-curry/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-curry/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-curry/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/curry/issues"
    },
    "contributors": [
        {
            "name": "Hugh FD Jackson"
        }
    ],
    "dependencies": {},
    "description": "flexible but simple curry function",
    "devDependencies": {
        "browserify": "2.17.2",
        "delve": "0.3.2",
        "lodash": "2.1.0",
        "mocha": "1.8.1",
        "uglify-js": "2.3.6"
    },
    "directories": {},
    "dist": {
        "shasum": "9e6dd289548dba7e653d5ae3fe903fe7dfb33af2",
        "tarball": "https://registry.npmjs.org/curry/-/curry-1.2.0.tgz"
    },
    "homepage": "https://github.com/dominictarr/curry",
    "main": "./curry",
    "maintainers": [
        {
            "name": "dominictarr"
        },
        {
            "name": "hughfdjackson"
        }
    ],
    "name": "curry",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/curry.git"
    },
    "scripts": {
        "prepublish": "./node_modules/browserify/bin/cmd.js --standalone curry -e curry.js | ./node_modules/uglify-js/bin/uglifyjs > curry.min.js",
        "test": "./node_modules/mocha/bin/mocha test"
    },
    "testling": {
        "files": "test/*-test.js",
        "browsers": [
            "iexplore/6.0",
            "iexplore/7.0",
            "iexplore/8.0",
            "iexplore/9.0",
            "iexplore/10.0",
            "chrome/4.0",
            "chrome/23.0",
            "firefox/3.0",
            "firefox/17.0",
            "safari/5.0.5",
            "safari/5.1"
        ],
        "harness": "mocha"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
