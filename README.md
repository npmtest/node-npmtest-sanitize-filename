# npmtest-sanitize-filename

#### basic test coverage for  [sanitize-filename (v1.6.1)](https://github.com/parshap/node-sanitize-filename#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sanitize-filename.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sanitize-filename) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sanitize-filename.svg)](https://travis-ci.org/npmtest/node-npmtest-sanitize-filename)

#### Sanitize a string for use as a filename

[![NPM](https://nodei.co/npm/sanitize-filename.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sanitize-filename)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sanitize-filename/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sanitize-filename/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sanitize-filename/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sanitize-filename/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sanitize-filename/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sanitize-filename/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sanitize-filename/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sanitize-filename/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sanitize-filename/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sanitize-filename/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sanitize-filename/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sanitize-filename/build/test-report.html](https://npmtest.github.io/node-npmtest-sanitize-filename/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sanitize-filename/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sanitize-filename/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sanitize-filename/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sanitize-filename/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sanitize-filename/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sanitize-filename/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sanitize-filename/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sanitize-filename/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Parsha Pourkhomami"
    },
    "bugs": {
        "url": "https://github.com/parshap/node-sanitize-filename/issues"
    },
    "contributors": [
        {
            "name": "Parsha Pourkhomami"
        },
        {
            "name": "Joel Mukuthu"
        }
    ],
    "dependencies": {
        "truncate-utf8-bytes": "^1.0.0"
    },
    "description": "Sanitize a string for use as a filename",
    "devDependencies": {
        "browserify": "^13.0.0",
        "concat-stream": "^1.5.1",
        "mktemp": "^0.4.0",
        "tape": "^4.2.2",
        "zuul": "^3.7.2"
    },
    "directories": {},
    "dist": {
        "shasum": "612da1c96473fa02dccda92dcd5b4ab164a6772a",
        "tarball": "https://registry.npmjs.org/sanitize-filename/-/sanitize-filename-1.6.1.tgz"
    },
    "gitHead": "ef1e8ad58e95eb90f8a01f209edf55cd4176e9c8",
    "homepage": "https://github.com/parshap/node-sanitize-filename#readme",
    "keywords": [
        "file",
        "name",
        "filename",
        "sanitize",
        "validate",
        "escape"
    ],
    "license": "WTFPL OR ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "parshap"
        }
    ],
    "name": "sanitize-filename",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/parshap/node-sanitize-filename.git"
    },
    "scripts": {
        "test": "tape test.js",
        "test-browser": "zuul --local --open -- test.js",
        "test-browser-sauce": "zuul -- test.js"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
