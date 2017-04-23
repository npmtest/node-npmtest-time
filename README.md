# npmtest-time

#### basic test coverage for  [time (v0.12.0)](https://github.com/TooTallNate/node-time#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-time.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-time) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-time.svg)](https://travis-ci.org/npmtest/node-npmtest-time)

#### "time.h" bindings for Node.js

[![NPM](https://nodei.co/npm/time.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/time)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-time/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-time/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-time/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-time/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-time/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-time/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-time/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-time/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-time/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-time/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-time/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-time/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-time/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-time/build/test-report.html](https://npmtest.github.io/node-npmtest-time/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-time/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-time/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-time/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-time/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-time/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-time/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-time/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-time/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Rajlich",
        "url": "http://tootallnate.net"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/node-time/issues"
    },
    "contributors": [
        {
            "name": "Diogo Resende"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.0",
        "debug": "^2.2.0",
        "nan": "^2.2.0"
    },
    "description": "\"time.h\" bindings for Node.js",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "755414bc3ef0a2ea44ce9f775bd3cf664ec49bb7",
        "tarball": "https://registry.npmjs.org/time/-/time-0.12.0.tgz"
    },
    "gitHead": "f88e1b1e71f7b5d9b9528e4b713a553219c64c03",
    "gypfile": true,
    "homepage": "https://github.com/TooTallNate/node-time#readme",
    "keywords": [
        "date",
        "time",
        "time.h",
        "timezone",
        "setTimezone",
        "getTimezone"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "TooTallNate"
        },
        {
            "name": "tootallnate"
        }
    ],
    "name": "time",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/node-time.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha --reporter spec"
    },
    "version": "0.12.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
