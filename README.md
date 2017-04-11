# test coverage for  [hiredis (v0.5.0)](http://github.com/redis/hiredis-node)  [![npm package](https://img.shields.io/npm/v/npmtest-hiredis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hiredis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hiredis.svg)](https://travis-ci.org/npmtest/node-npmtest-hiredis)
#### Wrapper for reply processing code in hiredis

[![NPM](https://nodei.co/npm/hiredis.png?downloads=true)](https://www.npmjs.com/package/hiredis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hiredis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hiredis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hiredis/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-hiredis/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-hiredis%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hiredis/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hiredis/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-hiredis%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hiredis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hiredis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jan-Erik Rediger",
        "email": "janerik@fnordig.de"
    },
    "bugs": {
        "url": "https://github.com/redis/hiredis-node/issues"
    },
    "contributors": [
        {
            "name": "Pieter Noordhuis",
            "email": "pcnoordhuis@gmail.com"
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
            "name": "pietern",
            "email": "pcnoordhuis@gmail.com"
        },
        {
            "name": "badboy_",
            "email": "janerik@fnordig.de"
        }
    ],
    "name": "hiredis",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/redis/hiredis-node.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/reader.js && node test/writer.js"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
