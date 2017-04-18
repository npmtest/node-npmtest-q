# npmtest-q

#### test coverage for  [q (v1.5.0)](https://github.com/kriskowal/q)  [![npm package](https://img.shields.io/npm/v/npmtest-q.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-q) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-q.svg)](https://travis-ci.org/npmtest/node-npmtest-q)

#### A library for promises (CommonJS/Promises/A,B,D)

[![NPM](https://nodei.co/npm/q.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/q)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-q/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-q/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-q/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-q/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-q/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-q/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-q/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-q/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-q/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-q/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-q/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-q/build/test-report.html](https://npmtest.github.io/node-npmtest-q/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-q/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-q/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-q/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-q/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-q/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-q/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-q/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-q/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kris Kowal",
        "url": "https://github.com/kriskowal"
    },
    "bugs": {
        "url": "http://github.com/kriskowal/q/issues"
    },
    "contributors": [
        {
            "name": "Kris Kowal",
            "url": "https://github.com/kriskowal"
        },
        {
            "name": "Irakli Gozalishvili",
            "url": "http://jeditoolkit.com"
        },
        {
            "name": "Domenic Denicola",
            "url": "http://domenicdenicola.com"
        }
    ],
    "dependencies": {},
    "description": "A library for promises (CommonJS/Promises/A,B,D)",
    "devDependencies": {
        "cover": "*",
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.9",
        "grunt-contrib-uglify": "~0.9.1",
        "jasmine-node": "1.11.0",
        "jshint": "~2.1.9",
        "matcha": "~0.2.0",
        "opener": "*",
        "promises-aplus-tests": "1.x"
    },
    "directories": {
        "test": "./spec"
    },
    "dist": {
        "shasum": "dd01bac9d06d30e6f219aecb8253ee9ebdc308f1",
        "tarball": "https://registry.npmjs.org/q/-/q-1.5.0.tgz"
    },
    "engines": {
        "node": ">=0.6.0",
        "teleport": ">=0.2.0"
    },
    "files": [
        "LICENSE",
        "q.js",
        "queue.js"
    ],
    "gitHead": "4fecabe07ff9f3683a3d4548e7f81c2aba693326",
    "homepage": "https://github.com/kriskowal/q",
    "keywords": [
        "q",
        "promise",
        "promises",
        "promises-a",
        "promises-aplus",
        "deferred",
        "future",
        "async",
        "flow control",
        "fluent",
        "browser",
        "node"
    ],
    "license": "MIT",
    "main": "q.js",
    "maintainers": [
        {
            "name": "kriskowal"
        },
        {
            "name": "domenic"
        }
    ],
    "name": "q",
    "optionalDependencies": {},
    "overlay": {
        "teleport": {
            "dependencies": {
                "system": ">=0.0.4"
            }
        }
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/kriskowal/q.git"
    },
    "scripts": {
        "benchmark": "matcha",
        "cover": "cover run jasmine-node spec && cover report html && opener cover_html/index.html",
        "lint": "jshint q.js",
        "minify": "grunt",
        "prepublish": "grunt",
        "test": "npm ls -s && jasmine-node spec && promises-aplus-tests spec/aplus-adapter && npm run -s lint",
        "test-browser": "opener spec/q-spec.html"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
