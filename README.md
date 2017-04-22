# npmtest-browser-request

#### basic test-coverage for  [browser-request (v0.3.3)](http://github.com/iriscouch/browser-request)  [![npm package](https://img.shields.io/npm/v/npmtest-browser-request.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browser-request) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browser-request.svg)](https://travis-ci.org/npmtest/node-npmtest-browser-request)

#### Browser port of the Node.js 'request' package

[![NPM](https://nodei.co/npm/browser-request.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-request)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browser-request/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-request/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browser-request/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browser-request/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browser-request/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browser-request/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browser-request/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browser-request/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browser-request/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-request/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browser-request/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browser-request/build/test-report.html](https://npmtest.github.io/node-npmtest-browser-request/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browser-request/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browser-request/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browser-request/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-request/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-request/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-request/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browser-request/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browser-request/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "browser-request",
    "version": "0.3.3",
    "author": {
        "name": "Jason Smith"
    },
    "description": "Browser port of the Node.js 'request' package",
    "keywords": [
        "request",
        "http",
        "browser",
        "browserify"
    ],
    "homepage": "http://github.com/iriscouch/browser-request",
    "repository": {
        "type": "git",
        "url": "git://github.com/iriscouch/browser-request"
    },
    "scripts": {
        "test": "beefy test.js"
    },
    "devDependencies": {
        "tape": "~1.0.4",
        "beefy": "~0.4.0",
        "browserify": "~2.25.0"
    },
    "engines": [
        "node"
    ],
    "testling": {
        "files": "test.js",
        "browsers": [
            "ie/6..latest",
            "firefox/3..5",
            "firefox/19..nightly",
            "chrome/4..7",
            "chrome/24..canary",
            "opera/10..next",
            "safari/4..latest",
            "iphone/6",
            "ipad/6"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
