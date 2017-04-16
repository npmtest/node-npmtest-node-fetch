# test coverage for  [node-fetch (v1.6.3)](https://github.com/bitinn/node-fetch)  [![npm package](https://img.shields.io/npm/v/npmtest-node-fetch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-fetch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-fetch.svg)](https://travis-ci.org/npmtest/node-npmtest-node-fetch)
#### A light-weight module that brings window.fetch to node.js and io.js

[![NPM](https://nodei.co/npm/node-fetch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-fetch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-fetch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-fetch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-fetch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-fetch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-fetch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-fetch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-fetch/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-fetch/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-fetch/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-fetch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-fetch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-fetch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Frank"
    },
    "bugs": {
        "url": "https://github.com/bitinn/node-fetch/issues"
    },
    "dependencies": {
        "encoding": "^0.1.11",
        "is-stream": "^1.0.1"
    },
    "description": "A light-weight module that brings window.fetch to node.js and io.js",
    "devDependencies": {
        "bluebird": "^3.3.4",
        "chai": "^3.5.0",
        "chai-as-promised": "^5.2.0",
        "coveralls": "^2.11.2",
        "form-data": ">=1.0.0",
        "istanbul": "^0.4.2",
        "mocha": "^2.1.0",
        "parted": "^0.1.1",
        "promise": "^7.1.1",
        "resumer": "0.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dc234edd6489982d58e8f0db4f695029abcd8c04",
        "tarball": "https://registry.npmjs.org/node-fetch/-/node-fetch-1.6.3.tgz"
    },
    "gitHead": "3c053ce32760d2d5d6cb8712fb4115b44e4083d4",
    "homepage": "https://github.com/bitinn/node-fetch",
    "keywords": [
        "fetch",
        "http",
        "promise"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bitinn"
        }
    ],
    "name": "node-fetch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bitinn/node-fetch.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha --report lcovonly -- -R spec test/test.js && cat ./coverage/lcov.info | coveralls",
        "report": "istanbul cover _mocha -- -R spec test/test.js",
        "test": "mocha test/test.js"
    },
    "version": "1.6.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
