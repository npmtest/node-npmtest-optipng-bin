# npmtest-optipng-bin

#### basic test coverage for  [optipng-bin (v3.1.4)](https://github.com/imagemin/optipng-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-optipng-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-optipng-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-optipng-bin.svg)](https://travis-ci.org/npmtest/node-npmtest-optipng-bin)

#### OptiPNG wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/optipng-bin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/optipng-bin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-optipng-bin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-optipng-bin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-optipng-bin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-optipng-bin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-optipng-bin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-optipng-bin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-optipng-bin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-optipng-bin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-optipng-bin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-optipng-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-optipng-bin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-optipng-bin/build/test-report.html](https://npmtest.github.io/node-npmtest-optipng-bin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-optipng-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-optipng-bin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-optipng-bin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-optipng-bin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-optipng-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-optipng-bin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-optipng-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-optipng-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "optipng": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/imagemin/optipng-bin/issues"
    },
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "description": "OptiPNG wrapper that makes it seamlessly available as a local dependency",
    "devDependencies": {
        "bin-check": "^1.0.0",
        "compare-size": "^1.0.1",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "path-exists": "^1.0.0",
        "rimraf": "^2.3.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "95d34f2c488704f6fd70606bfea0c659f1d95d84",
        "tarball": "https://registry.npmjs.org/optipng-bin/-/optipng-bin-3.1.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "cli.js",
        "lib"
    ],
    "gitHead": "6bc08279f23be59d8ef2e430fc702767ce840601",
    "homepage": "https://github.com/imagemin/optipng-bin#readme",
    "keywords": [
        "compress",
        "image",
        "img",
        "minify",
        "optimize",
        "png"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "1000ch"
        },
        {
            "name": "bradbaris"
        },
        {
            "name": "kevva"
        },
        {
            "name": "shinnn"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "optipng-bin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/imagemin/optipng-bin.git"
    },
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha --timeout 50000"
    },
    "version": "3.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
