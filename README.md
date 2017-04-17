# test coverage for  [dom-delegator (v13.1.0)](https://github.com/Raynos/dom-delegator)  [![npm package](https://img.shields.io/npm/v/npmtest-dom-delegator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dom-delegator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dom-delegator.svg)](https://travis-ci.org/npmtest/node-npmtest-dom-delegator)
#### Decorate elements with delegated events

[![NPM](https://nodei.co/npm/dom-delegator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dom-delegator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dom-delegator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dom-delegator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dom-delegator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dom-delegator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dom-delegator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dom-delegator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dom-delegator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dom-delegator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dom-delegator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dom-delegator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dom-delegator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dom-delegator/build/test-report.html](https://npmtest.github.io/node-npmtest-dom-delegator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dom-delegator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dom-delegator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dom-delegator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dom-delegator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dom-delegator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dom-delegator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dom-delegator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dom-delegator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/dom-delegator/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "cuid": "^1.2.4",
        "ev-store": "^7.0.0",
        "global": "^4.2.1",
        "individual": "^2.0.0",
        "inherits": "^2.0.1",
        "weakmap-shim": "^1.0.0",
        "xtend": "^2.2.0"
    },
    "description": "Decorate elements with delegated events",
    "devDependencies": {
        "cuid": "^1.2.4",
        "event-sinks": "~1.0.1",
        "istanbul": "^0.2.6",
        "jshint": "^2.5.0",
        "pre-commit": "0.0.5",
        "run-browser": "^1.3.1",
        "synthetic-dom-events": "git://github.com/Raynos/synthetic-dom-events.git",
        "tap-spec": "^0.1.9",
        "tape": "^2.12.3"
    },
    "directories": {},
    "dist": {
        "shasum": "f82cc535866a1878d9b4696d3befaeb4b5dad4b3",
        "tarball": "https://registry.npmjs.org/dom-delegator/-/dom-delegator-13.1.0.tgz"
    },
    "gitHead": "273f5da04c4dbea3eafee17e02d59e78125972b1",
    "homepage": "https://github.com/Raynos/dom-delegator",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/dom-delegator/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos"
        }
    ],
    "name": "dom-delegator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/dom-delegator.git"
    },
    "scripts": {
        "browser": "run-browser ./test/index.js",
        "cover": "istanbul cover --print detail ./test/index.js",
        "phantom": "run-browser ./test/index.js -b | tap-spec",
        "test": "jshint . && node ./test/index.js | tap-spec",
        "view-cover": "istanbul report html && google-chrome ./coverage/index.html"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "13.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
