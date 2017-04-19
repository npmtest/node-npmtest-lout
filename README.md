# npmtest-lout

#### basic test coverage for  [lout (v10.0.1)](https://github.com/hapijs/lout#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lout.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lout) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lout.svg)](https://travis-ci.org/npmtest/node-npmtest-lout)

#### API documentation generator plugin for hapi

[![NPM](https://nodei.co/npm/lout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lout)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lout/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lout/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lout/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lout/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lout/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lout/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lout/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lout/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lout/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lout/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lout/build/test-report.html](https://npmtest.github.io/node-npmtest-lout/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lout/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lout/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/lout/issues"
    },
    "dependencies": {
        "boom": "4.x.x",
        "handlebars": "4.x.x",
        "hoek": "4.x.x"
    },
    "description": "API documentation generator plugin for hapi",
    "devDependencies": {
        "cheerio": "0.x.x",
        "code": "4.x.x",
        "hapi": ">= 11",
        "inert": ">= 3.x.x",
        "joi": ">= 10.x.x",
        "lab": "12.x.x",
        "vision": ">= 4.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "7f80e580cc68b773a3a5dbbb4e57d2a27cf22532",
        "tarball": "https://registry.npmjs.org/lout/-/lout-10.0.1.tgz"
    },
    "engines": {
        "node": ">= 4.x.x",
        "npm": ">= 3.x"
    },
    "gitHead": "ae9b9cb1996bb220a8048a3c769422148b27409a",
    "homepage": "https://github.com/hapijs/lout#readme",
    "keywords": [
        "docs",
        "hapi"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        },
        {
            "name": "marsup"
        }
    ],
    "name": "lout",
    "optionalDependencies": {},
    "peerDependencies": {
        "hapi": ">= 16",
        "inert": ">= 4.x.x",
        "joi": ">= 10.x.x",
        "vision": ">= 4.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/lout.git"
    },
    "scripts": {
        "test": "lab -r console -t 100 -a code -L",
        "test-cov-html": "lab -r html -o coverage.html -a code -L"
    },
    "version": "10.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
