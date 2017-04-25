# npmtest-gulp-json-sass

#### basic test coverage for  [gulp-json-sass (v0.0.2)](https://github.com/rbalicki2/gulp-json-sass)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-json-sass.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-json-sass) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-json-sass.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-json-sass)

#### Gulp plugin for turning JSON files into files of scss/sass variable definitions.

[![NPM](https://nodei.co/npm/gulp-json-sass.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-json-sass)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-json-sass/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-json-sass/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-json-sass/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-json-sass/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-json-sass/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-json-sass/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-json-sass/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-json-sass/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-json-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-json-sass/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-json-sass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/rbalicki2/gulp-json-sass/issues"
    },
    "dependencies": {
        "chalk": "^0.5.1",
        "gulp-match": "^0.2.0",
        "gulp-util": "^3.0.0",
        "through": "^2.3.4"
    },
    "description": "Gulp plugin for turning JSON files into files of scss/sass variable definitions.",
    "devDependencies": {
        "gulp": "^3.8.6",
        "gulp-concat": "^2.3.4",
        "gulp-ruby-sass": "^0.7.1",
        "tape": "^2.14.0",
        "through2": "^0.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a3f1d8716e90023cb740299b2e8d785a28d89673",
        "tarball": "https://registry.npmjs.org/gulp-json-sass/-/gulp-json-sass-0.0.2.tgz"
    },
    "homepage": "https://github.com/rbalicki2/gulp-json-sass",
    "keywords": [
        "gulp",
        "json",
        "sass",
        "scss",
        "css"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rbalicki"
        }
    ],
    "name": "gulp-json-sass",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rbalicki2/gulp-json-sass.git"
    },
    "scripts": {
        "coverage": "istanbul cover test/*.js",
        "rm": "rimraf ./coverage",
        "test": "npm run coverage && npm run rm"
    },
    "version": "0.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
