# npmtest-globby

#### test coverage for  [globby (v6.1.0)](https://github.com/sindresorhus/globby#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-globby.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-globby) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-globby.svg)](https://travis-ci.org/npmtest/node-npmtest-globby)

#### Extends `glob` with support for multiple patterns and exposes a Promise API

[![NPM](https://nodei.co/npm/globby.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/globby)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-globby/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-globby/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-globby/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-globby/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-globby/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-globby/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-globby/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-globby/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-globby/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-globby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-globby/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-globby/build/test-report.html](https://npmtest.github.io/node-npmtest-globby/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-globby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-globby/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-globby/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-globby/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-globby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-globby/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-globby/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-globby/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/globby/issues"
    },
    "dependencies": {
        "array-union": "^1.0.1",
        "glob": "^7.0.3",
        "object-assign": "^4.0.1",
        "pify": "^2.0.0",
        "pinkie-promise": "^2.0.0"
    },
    "description": "Extends 'glob' with support for multiple patterns and exposes a Promise API",
    "devDependencies": {
        "ava": "*",
        "glob-stream": "github:gulpjs/glob-stream#master",
        "globby": "github:sindresorhus/globby#master",
        "matcha": "^0.7.0",
        "rimraf": "^2.2.8",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f5a6d70e8395e21c858fb0489d64df02424d506c",
        "tarball": "https://registry.npmjs.org/globby/-/globby-6.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "5c647384e349e90a13658778029b96b28112a972",
    "homepage": "https://github.com/sindresorhus/globby#readme",
    "keywords": [
        "all",
        "array",
        "directories",
        "dirs",
        "expand",
        "files",
        "filesystem",
        "filter",
        "find",
        "fnmatch",
        "folders",
        "fs",
        "glob",
        "globbing",
        "globs",
        "gulpfriendly",
        "match",
        "matcher",
        "minimatch",
        "multi",
        "multiple",
        "paths",
        "pattern",
        "patterns",
        "traverse",
        "util",
        "utility",
        "wildcard",
        "wildcards",
        "promise"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "schnittstabil"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "ult_combo"
        }
    ],
    "name": "globby",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/globby.git"
    },
    "scripts": {
        "bench": "npm update glob-stream && matcha bench.js",
        "test": "xo && ava"
    },
    "version": "6.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
