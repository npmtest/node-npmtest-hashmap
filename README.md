# npmtest-hashmap

#### basic test coverage for  [hashmap (v2.1.0)](https://github.com/flesler/hashmap)  [![npm package](https://img.shields.io/npm/v/npmtest-hashmap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hashmap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hashmap.svg)](https://travis-ci.org/npmtest/node-npmtest-hashmap)

#### HashMap Class for JavaScript

[![NPM](https://nodei.co/npm/hashmap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hashmap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hashmap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hashmap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hashmap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hashmap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hashmap/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hashmap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hashmap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hashmap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hashmap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hashmap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hashmap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hashmap/build/test-report.html](https://npmtest.github.io/node-npmtest-hashmap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hashmap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hashmap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hashmap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hashmap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hashmap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hashmap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hashmap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hashmap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hashmap",
    "author": "Ariel Flesler <aflesler@gmail.com>",
    "version": "2.1.0",
    "description": "HashMap Class for JavaScript",
    "keywords": [
        "hashmap",
        "map",
        "object",
        "array",
        "associative",
        "javascript",
        "nodejs",
        "node",
        "browser"
    ],
    "license": "MIT",
    "homepage": "https://github.com/flesler/hashmap",
    "bugs": "https://github.com/flesler/hashmap/issues",
    "repository": "git://github.com/flesler/hashmap",
    "main": "./hashmap.js",
    "scripts": {
        "precommit": "jshint hashmap.js",
        "prepush": "mocha test/ --reporter dot"
    },
    "engines": {
        "node": "*"
    },
    "dependencies": {},
    "devDependencies": {
        "chai": "3.5.0",
        "husky": "0.11.4",
        "jshint": "2.9.2",
        "mocha": "2.5.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
