# npmtest-showdown

#### basic test coverage for  [showdown (v1.6.4)](http://showdownjs.github.io/showdown/)  [![npm package](https://img.shields.io/npm/v/npmtest-showdown.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-showdown) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-showdown.svg)](https://travis-ci.org/npmtest/node-npmtest-showdown)

#### A Markdown to HTML converter written in Javascript

[![NPM](https://nodei.co/npm/showdown.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/showdown)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-showdown/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-showdown/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-showdown/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-showdown/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-showdown/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-showdown/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-showdown/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-showdown/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-showdown/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-showdown/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-showdown/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-showdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-showdown/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-showdown/build/test-report.html](https://npmtest.github.io/node-npmtest-showdown/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-showdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-showdown/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-showdown/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-showdown/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-showdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-showdown/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-showdown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-showdown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Estevão Santos"
    },
    "bin": {
        "showdown": "bin/showdown.js"
    },
    "bugs": {
        "url": "https://github.com/showdownjs/showdown/issues"
    },
    "contributors": [
        {
            "name": "John Gruber"
        },
        {
            "name": "John Fraser"
        },
        {
            "name": "Corey Innis"
        },
        {
            "name": "Remy Sharp"
        },
        {
            "name": "Konstantin Käfer"
        },
        {
            "name": "Roger Braun"
        },
        {
            "name": "Dominic Tarr"
        },
        {
            "name": "Cat Chen"
        },
        {
            "name": "Titus Stone"
        },
        {
            "name": "Rob Sutherland"
        },
        {
            "name": "Pavel Lang"
        },
        {
            "name": "Ben Combee"
        },
        {
            "name": "Adam Backstrom"
        },
        {
            "name": "Pascal Deschênes"
        },
        {
            "name": "Estevão Santos"
        }
    ],
    "dependencies": {
        "yargs": "^6.6.0"
    },
    "description": "A Markdown to HTML converter written in Javascript",
    "devDependencies": {
        "chai": "^3.5.0",
        "grunt": "^1.0.1",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-conventional-github-releaser": "^1.0.0",
        "grunt-endline": "^0.6.1",
        "grunt-eslint": "^19.0.0",
        "grunt-simple-mocha": "^0.4.0",
        "js-beautify": "^1.5.6",
        "load-grunt-tasks": "^3.2.0",
        "performance-now": "^2.0.0",
        "quiet-grunt": "^0.2.3",
        "semver": "^5.0.0",
        "semver-sort": "0.0.4",
        "sinon": "^1.14.1",
        "source-map-support": "^0.4.11"
    },
    "directories": {},
    "dist": {
        "shasum": "056bbb654ecdb8d8643ae12d6d597893ccaf46c6",
        "tarball": "https://registry.npmjs.org/showdown/-/showdown-1.6.4.tgz"
    },
    "gitHead": "072973ab8b027b86fb54bc6eb59850dc80f42b3a",
    "homepage": "http://showdownjs.github.io/showdown/",
    "keywords": [
        "markdown",
        "converter"
    ],
    "license": "BSD-3-Clause",
    "main": "./dist/showdown.js",
    "maintainers": [
        {
            "name": "coreyti"
        },
        {
            "name": "pdeschen"
        },
        {
            "name": "tivie"
        }
    ],
    "name": "showdown",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/showdownjs/showdown.git",
        "web": "https://github.com/showdownjs/showdown"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.6.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
