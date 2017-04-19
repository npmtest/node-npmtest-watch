# npmtest-watch

#### basic test coverage for  [watch (v1.0.2)](https://github.com/mikeal/watch)  [![npm package](https://img.shields.io/npm/v/npmtest-watch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-watch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-watch.svg)](https://travis-ci.org/npmtest/node-npmtest-watch)

#### Utilities for watching file trees.

[![NPM](https://nodei.co/npm/watch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/watch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-watch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-watch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-watch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-watch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-watch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-watch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-watch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-watch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-watch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-watch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-watch/build/test-report.html](https://npmtest.github.io/node-npmtest-watch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-watch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-watch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-watch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-watch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-watch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-watch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-watch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikeal Rogers"
    },
    "bin": {
        "watch": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/mikeal/watch/issues"
    },
    "dependencies": {
        "exec-sh": "^0.2.0",
        "minimist": "^1.2.0"
    },
    "description": "Utilities for watching file trees.",
    "devDependencies": {},
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "340a717bde765726fa0aa07d721e0147a551df0c",
        "tarball": "https://registry.npmjs.org/watch/-/watch-1.0.2.tgz"
    },
    "engines": {
        "node": ">=0.1.95"
    },
    "gitHead": "07e57379393271f33e3d30153fbaa4b790e6ff04",
    "homepage": "https://github.com/mikeal/watch",
    "keywords": [
        "util",
        "utility",
        "fs",
        "files"
    ],
    "license": "Apache-2.0",
    "main": "./main",
    "maintainers": [
        {
            "name": "finnpauls"
        },
        {
            "name": "levithomason"
        },
        {
            "name": "mikeal"
        }
    ],
    "name": "watch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mikeal/watch.git"
    },
    "scripts": {
        "release:major": "bash scripts/release.sh major",
        "release:minor": "bash scripts/release.sh minor",
        "release:patch": "bash scripts/release.sh patch"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
