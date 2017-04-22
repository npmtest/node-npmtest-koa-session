# npmtest-koa-session

#### basic test coverage for  koa-session (v5.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-session.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-session) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-session.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-session)

#### Koa cookie session middleware

[![NPM](https://nodei.co/npm/koa-session.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-session)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-session/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-session/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-session/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-session/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-session/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-session/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-session/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-session/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-session/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-session/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-session/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-session/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-session/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-session/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-session/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-session/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-session/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-session/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-session",
    "description": "Koa cookie session middleware",
    "repository": "koajs/session",
    "version": "5.0.0",
    "keywords": [
        "koa",
        "middleware",
        "session",
        "cookie"
    ],
    "files": [
        "index.js",
        "lib"
    ],
    "devDependencies": {
        "eslint": "3",
        "eslint-config-egg": "3",
        "istanbul": "0",
        "koa": "2",
        "mm": "^2.1.0",
        "mocha": "3",
        "should": "8",
        "supertest": "2"
    },
    "license": "MIT",
    "dependencies": {
        "crc": "^3.4.4",
        "debug": "^2.2.0",
        "uid-safe": "^2.1.3"
    },
    "engines": {
        "node": ">=7.6"
    },
    "scripts": {
        "test": "npm run lint && NODE_ENV=test mocha --require should --reporter spec test/*.test.js",
        "test-cov": "NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should test/*.test.js",
        "test-travis": "npm run lint && NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should test/*.test.js",
        "lint": "eslint lib test index.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
