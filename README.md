# npmtest-asar

#### basic test coverage for  [asar (v0.13.0)](https://github.com/electron/asar)  [![npm package](https://img.shields.io/npm/v/npmtest-asar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-asar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-asar.svg)](https://travis-ci.org/npmtest/node-npmtest-asar)

#### Creating Electron app packages

[![NPM](https://nodei.co/npm/asar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/asar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-asar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-asar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-asar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-asar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-asar/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-asar/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-asar/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-asar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-asar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-asar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-asar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-asar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-asar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-asar/build/test-report.html](https://npmtest.github.io/node-npmtest-asar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-asar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-asar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-asar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-asar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-asar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-asar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-asar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-asar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "asar": "./bin/asar.js"
    },
    "bugs": {
        "url": "https://github.com/electron/asar/issues"
    },
    "dependencies": {
        "chromium-pickle-js": "^0.2.0",
        "commander": "^2.9.0",
        "cuint": "^0.2.1",
        "glob": "^6.0.4",
        "minimatch": "^3.0.3",
        "mkdirp": "^0.5.0",
        "mksnapshot": "^0.3.0",
        "tmp": "0.0.28"
    },
    "description": "Creating Electron app packages",
    "devDependencies": {
        "lodash": "^4.2.1",
        "mocha": "^2.0.1",
        "rimraf": "^2.5.1",
        "standard": "^8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "df33dd9d01bff842464d0d9f095740d4a62afb14",
        "tarball": "https://registry.npmjs.org/asar/-/asar-0.13.0.tgz"
    },
    "engines": {
        "node": ">=4.6"
    },
    "gitHead": "6034e128913818d90f5986000b39d28829340dd4",
    "homepage": "https://github.com/electron/asar",
    "license": "MIT",
    "main": "./lib/asar.js",
    "maintainers": [
        {
            "name": "atom"
        },
        {
            "name": "electron"
        },
        {
            "name": "jlord"
        },
        {
            "name": "kevinsawicki"
        },
        {
            "name": "maxbrunsfeld"
        },
        {
            "name": "nathansobo"
        },
        {
            "name": "zcbenz"
        },
        {
            "name": "zeke"
        }
    ],
    "name": "asar",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/electron/asar.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "mocha --reporter spec && npm run lint"
    },
    "standard": {
        "env": {
            "mocha": true
        }
    },
    "version": "0.13.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
