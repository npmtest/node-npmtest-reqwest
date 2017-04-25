# npmtest-reqwest

#### basic test coverage for  [reqwest (v2.0.5)](https://github.com/ded/reqwest)  [![npm package](https://img.shields.io/npm/v/npmtest-reqwest.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-reqwest) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-reqwest.svg)](https://travis-ci.org/npmtest/node-npmtest-reqwest)

#### A wrapper for asynchronous http requests

[![NPM](https://nodei.co/npm/reqwest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reqwest)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-reqwest/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-reqwest/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-reqwest/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-reqwest/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-reqwest/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-reqwest/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-reqwest/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-reqwest/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-reqwest/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-reqwest/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-reqwest/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-reqwest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-reqwest/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-reqwest/build/test-report.html](https://npmtest.github.io/node-npmtest-reqwest/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-reqwest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-reqwest/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-reqwest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reqwest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reqwest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reqwest/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-reqwest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-reqwest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dustin Diaz",
        "url": "http://dustindiaz.com"
    },
    "browser": {
        "xhr2": false
    },
    "bugs": {
        "url": "https://github.com/ded/reqwest/issues"
    },
    "dependencies": {},
    "description": "A wrapper for asynchronous http requests",
    "devDependencies": {
        "bump": "0.2.3",
        "connect": "1.8.x",
        "delayed-stream": "0.0.5",
        "dispatch": "0.x.x",
        "mime": "1.x.x",
        "sink-test": ">=0.1.2",
        "smoosh": "0.4.0",
        "valentine": ">=1.4.7"
    },
    "directories": {},
    "dist": {
        "shasum": "00fb15ac4918c419ca82b43f24c78882e66039a1",
        "tarball": "https://registry.npmjs.org/reqwest/-/reqwest-2.0.5.tgz"
    },
    "ender": "./src/ender.js",
    "gitHead": "d9be8c54a65bc54a8fa5ca8e9a719c51abf44996",
    "homepage": "https://github.com/ded/reqwest",
    "keywords": [
        "ender",
        "ajax",
        "xhr",
        "connection",
        "web 2.0",
        "async",
        "sync"
    ],
    "license": "MIT",
    "main": "./reqwest.js",
    "maintainers": [
        {
            "name": "ded"
        },
        {
            "name": "rvagg"
        }
    ],
    "name": "reqwest",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ded/reqwest.git"
    },
    "scripts": {
        "boosh": "smoosh make ./build.json",
        "test": "node ./test.js"
    },
    "spm": {
        "main": "reqwest.js",
        "ignore": [
            "vendor",
            "test",
            "make"
        ]
    },
    "version": "2.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
