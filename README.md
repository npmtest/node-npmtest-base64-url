# npmtest-base64-url

#### test coverage for  [base64-url (v1.3.3)](https://github.com/joaquimserafim/base64-url)  [![npm package](https://img.shields.io/npm/v/npmtest-base64-url.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-base64-url) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-base64-url.svg)](https://travis-ci.org/npmtest/node-npmtest-base64-url)

#### Base64 encode, decode, escape and unescape for URL applications

[![NPM](https://nodei.co/npm/base64-url.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/base64-url)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-base64-url/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-base64-url/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-base64-url/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-base64-url/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-base64-url/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-base64-url/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-base64-url/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-base64-url/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-base64-url/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-base64-url/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-base64-url/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-base64-url/build/test-report.html](https://npmtest.github.io/node-npmtest-base64-url/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-base64-url/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-base64-url/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-base64-url/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-base64-url/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-base64-url/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-base64-url/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-base64-url/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-base64-url/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "@joaquimserafim"
    },
    "bugs": {
        "url": "https://github.com/joaquimserafim/base64-url/issues"
    },
    "dependencies": {},
    "description": "Base64 encode, decode, escape and unescape for URL applications",
    "devDependencies": {
        "istanbul": "^0.3.5",
        "jscs": "^1.9.0",
        "jshint": "^2.5.11",
        "pre-commit": "^1.1.3",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f8b6c537f09a4fc58c99cb86e0b0e9c61461a20f",
        "tarball": "https://registry.npmjs.org/base64-url/-/base64-url-1.3.3.tgz"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "fb100b8397f24b1066016cf09369a7b2be4e1a32",
    "homepage": "https://github.com/joaquimserafim/base64-url",
    "keywords": [
        "base64",
        "base64url"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "quim"
        }
    ],
    "name": "base64-url",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "style",
        "test",
        "coverage:check"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/joaquimserafim/base64-url.git"
    },
    "scripts": {
        "coverage": "open coverage/lcov-report/index.html",
        "coverage:check": "istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "lint": "jshint -c .jshintrc *.js",
        "style": "jscs -p google *.js",
        "test": "istanbul cover tape test.js"
    },
    "version": "1.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
