# npmtest-express-validation

#### basic test coverage for  [express-validation (v1.0.2)](https://github.com/andrewkeig/express-validation)  [![npm package](https://img.shields.io/npm/v/npmtest-express-validation.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-validation) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-validation.svg)](https://travis-ci.org/npmtest/node-npmtest-express-validation)

#### express-validation is a middleware that validates the body, params, query, headers and cookies of a request and returns a response with errors; if any of the configured validation rules fail.

[![NPM](https://nodei.co/npm/express-validation.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-validation)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-validation/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-validation/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-validation/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-validation/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-validation/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-validation/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-validation/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-validation/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-validation/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-validation/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-validation/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-validation/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-validation/build/test-report.html](https://npmtest.github.io/node-npmtest-express-validation/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-validation/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-validation/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-validation/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-validation/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-validation/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-validation/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Keig"
    },
    "bugs": {
        "url": "https://github.com/andrewkeig/express-validation/issues"
    },
    "contributors": [
        {
            "name": "Valerio Coltre"
        }
    ],
    "dependencies": {
        "lodash": "^4.9.0"
    },
    "description": "express-validation is a middleware that validates the body, params, query, headers and cookies of a request and returns a response with errors; if any of the configured validation rules fail.",
    "devDependencies": {
        "body-parser": "^1.14.2",
        "cookie-parser": "^1.4.1",
        "eslint": "^2.7.0",
        "express": "~4.x",
        "joi": "^9.0.4",
        "mocha": "^2.3.4",
        "should": "^9.0.2",
        "supertest": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7d589dd3b257c55b3e004665b6c69cb12cc2b142",
        "tarball": "https://registry.npmjs.org/express-validation/-/express-validation-1.0.2.tgz"
    },
    "gitHead": "911c1f8d365b0cd7725d6be1d208c10bb7ed0df0",
    "homepage": "https://github.com/andrewkeig/express-validation",
    "keywords": [
        "express",
        "validation",
        "validate"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/andrewkeig/express-validation/raw/master/LICENSE"
        }
    ],
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "airasoul"
        },
        {
            "name": "colthreepv"
        }
    ],
    "name": "express-validation",
    "optionalDependencies": {},
    "peerDependencies": {
        "joi": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andrewkeig/express-validation.git"
    },
    "scripts": {
        "pretest": "eslint lib",
        "test": "mocha -R spec -b"
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
