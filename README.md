# npmtest-wrench

#### test coverage for  [wrench (v1.5.9)](https://github.com/ryanmcgrath/wrench-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-wrench.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wrench) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wrench.svg)](https://travis-ci.org/npmtest/node-npmtest-wrench)

#### Recursive filesystem (and other) operations that Node *should* have.

[![NPM](https://nodei.co/npm/wrench.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wrench)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wrench/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wrench/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wrench/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wrench/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wrench/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wrench/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wrench/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wrench/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wrench/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wrench/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wrench/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wrench/build/test-report.html](https://npmtest.github.io/node-npmtest-wrench/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wrench/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wrench/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wrench/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wrench/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wrench/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wrench/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wrench/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wrench/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ryan McGrath"
    },
    "bugs": {
        "url": "http://github.com/ryanmcgrath/wrench-js/issues"
    },
    "dependencies": {},
    "deprecated": "wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.",
    "description": "Recursive filesystem (and other) operations that Node *should* have.",
    "devDependencies": {
        "nodeunit": ">= 0.6.4"
    },
    "directories": {
        "lib": "./lib/"
    },
    "dist": {
        "shasum": "411691c63a9b2531b1700267279bdeca23b2142a",
        "tarball": "https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz"
    },
    "engines": {
        "node": ">=0.1.97"
    },
    "gitHead": "2cffe4e3f4219dc94a9e0e3d9307391c4c5e1619",
    "homepage": "https://github.com/ryanmcgrath/wrench-js#readme",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/ryanmcgrath/wrench-js/raw/master/LICENSE"
        }
    ],
    "main": "./lib/wrench",
    "maintainers": [
        {
            "name": "ryanmcgrath"
        }
    ],
    "name": "wrench",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://ryanmcgrath@github.com/ryanmcgrath/wrench-js.git"
    },
    "scripts": {
        "test": "nodeunit tests/runner.js"
    },
    "version": "1.5.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
