# npmdoc-google-spreadsheets

#### api documentation for  [google-spreadsheets (v0.5.1)](https://github.com/samcday/node-google-spreadsheets)  [![npm package](https://img.shields.io/npm/v/npmdoc-google-spreadsheets.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-google-spreadsheets) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-google-spreadsheets.svg)](https://travis-ci.org/npmdoc/node-npmdoc-google-spreadsheets)

#### Google Spreadsheet Data API for Node.js

[![NPM](https://nodei.co/npm/google-spreadsheets.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-spreadsheets)

- [https://npmdoc.github.io/node-npmdoc-google-spreadsheets/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-spreadsheets/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-spreadsheets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-spreadsheets/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-google-spreadsheets/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-google-spreadsheets/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sam",
        "url": "http://samcday.com.au/"
    },
    "browser": {
        "request": "browser-request"
    },
    "bugs": {
        "url": "https://github.com/samcday/node-google-spreadsheets/issues"
    },
    "dependencies": {
        "request": "^2.65.0",
        "semver": "^5.0.3",
        "statuses": "^1.2.1"
    },
    "description": "Google Spreadsheet Data API for Node.js",
    "devDependencies": {
        "browser-request": "^0.3.3",
        "browserify": "^12.0.1",
        "googleapis": "^2.1.6",
        "istanbul": "^0.4.0",
        "mocha": "^2.3.3",
        "mochify": "^2.14.2",
        "should": "^7.1.1",
        "uglifyjs": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "84f3c86f3f7303a134c0caeca8b9a42077b112ea",
        "tarball": "https://registry.npmjs.org/google-spreadsheets/-/google-spreadsheets-0.5.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "a30afe3876c44ba8b95ff1e5ff5e120174d2c67a",
    "homepage": "https://github.com/samcday/node-google-spreadsheets",
    "jshintConfig": {
        "node": true,
        "mocha": true,
        "newcap": false
    },
    "license": "Unlicense",
    "main": "lib/spreadsheets.js",
    "maintainers": [
        {
            "name": "samcday"
        }
    ],
    "name": "google-spreadsheets",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/samcday/node-google-spreadsheets.git"
    },
    "scripts": {
        "browser-test": "mochify -R spec --ignore-ssl-errors",
        "build": "browserify --standalone Spreadsheets lib/spreadsheets.js -o lib/spreadsheets.browser.js && uglifyjs lib/spreadsheets.browser.js -o lib/spreadsheets.browser.min.js",
        "test": "istanbul test _mocha"
    },
    "version": "0.5.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
