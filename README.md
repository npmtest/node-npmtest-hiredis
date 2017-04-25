# npmtest-hiredis

#### basic test coverage for  [hiredis (v0.5.0)](http://github.com/redis/hiredis-node)  [![npm package](https://img.shields.io/npm/v/npmtest-hiredis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hiredis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hiredis.svg)](https://travis-ci.org/npmtest/node-npmtest-hiredis)

#### Wrapper for reply processing code in hiredis

[![NPM](https://nodei.co/npm/hiredis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hiredis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hiredis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hiredis/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hiredis/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hiredis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hiredis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hiredis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hiredis/build/test-report.html](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hiredis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hiredis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hiredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hiredis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jan-Erik Rediger"
    },
    "bugs": {
        "url": "https://github.com/redis/hiredis-node/issues"
    },
    "contributors": [
        {
            "name": "Pieter Noordhuis"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.4"
    },
    "description": "Wrapper for reply processing code in hiredis",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "db03a98becd7003d13c260043aceecfacdf59b87",
        "tarball": "https://registry.npmjs.org/hiredis/-/hiredis-0.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "b8f3af63704176a323afed2a0e9bb4811d201bc1",
    "gypfile": true,
    "homepage": "http://github.com/redis/hiredis-node",
    "license": "BSD-3-Clause",
    "main": "hiredis",
    "maintainers": [
        {
            "name": "pietern"
        },
        {
            "name": "badboy_"
        }
    ],
    "name": "hiredis",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/redis/hiredis-node.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/reader.js && node test/writer.js"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
