# npmtest-mysql-promise

test coverage for  [mysql-promise (v4.1.0)](https://github.com/martinj/node-mysql-promise#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mysql-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mysql-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mysql-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-mysql-promise)
#### Small wrapper for mysql that use promises.

[![NPM](https://nodei.co/npm/mysql-promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mysql-promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mysql-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mysql-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mysql-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mysql-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mysql-promise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mysql-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mysql-promise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mysql-promise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mysql-promise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mysql-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mysql-promise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mysql-promise/build/test-report.html](https://npmtest.github.io/node-npmtest-mysql-promise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mysql-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mysql-promise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mysql-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mysql-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mysql-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Martin Jonsson"
    },
    "bugs": {
        "url": "https://github.com/martinj/node-mysql-promise/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.6",
        "mysql": "^2.12.0"
    },
    "description": "Small wrapper for mysql that use promises.",
    "devDependencies": {
        "@aptoma/eslint-config": "^5.0.1",
        "eslint": "^2.13.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.2",
        "mysql2": "^1.1.2",
        "release-it": "^2.5.1",
        "should": "^11.1.1",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "43e292c60c3a5c8e4f4d2f8bf3747a318d4aba6b",
        "tarball": "https://registry.npmjs.org/mysql-promise/-/mysql-promise-4.1.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "43891d75917edc8a51c153b59bf6fe8687438c10",
    "greenkeeper": {
        "ignore": [
            "eslint"
        ]
    },
    "homepage": "https://github.com/martinj/node-mysql-promise#readme",
    "keywords": [
        "mysql",
        "promise"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "martinj"
        }
    ],
    "name": "mysql-promise",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/martinj/node-mysql-promise.git"
    },
    "scripts": {
        "lint": "eslint --ext '.js' test index.js",
        "release": "npm test && release-it -n -i patch",
        "release:major": "npm test && release-it -n -i major",
        "release:minor": "npm test && release-it -n -i minor",
        "test": "NODE_ENV=test npm run lint && istanbul cover -i 'index.js' _mocha -- -u exports -R spec 'test/**/*.test.js'"
    },
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
