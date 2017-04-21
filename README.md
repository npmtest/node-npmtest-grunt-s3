# npmtest-grunt-s3

#### basic test coverage for  [grunt-s3 (v0.2.0-alpha.3)](https://github.com/pifantastic/grunt-s3)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-s3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-s3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-s3.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-s3)

#### A grunt task to automate moving files to/from Amazon S3.

[![NPM](https://nodei.co/npm/grunt-s3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-s3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-s3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-s3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-s3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-s3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-s3/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-s3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-s3/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-s3/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-s3/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-s3/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-s3/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-s3/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-s3/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-s3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-s3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-s3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-s3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-s3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-s3",
    "description": "A grunt task to automate moving files to/from Amazon S3.",
    "version": "0.2.0-alpha.3",
    "author": "Aaron Forsander (https://github.com/pifantastic)",
    "homepage": "https://github.com/pifantastic/grunt-s3",
    "repository": {
        "type": "git",
        "url": "git://github.com/pifantastic/grunt-s3.git"
    },
    "bugs": {
        "url": "https://github.com/pifantastic/grunt-s3/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/pifantastic/grunt-s3/blob/master/LICENSE"
        }
    ],
    "main": "tasks/s3",
    "bin": "bin/grunt-s3",
    "scripts": {
        "test": "grunt test",
        "fakes3": "fakes3 -r s3 -p 1337"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "keywords": [
        "gruntplugin",
        "amazon",
        "s3"
    ],
    "dependencies": {
        "grunt": "0.4.x",
        "underscore.deferred": "~0.1.4",
        "knox": "0.8.x",
        "mime": "~1.2.5",
        "temporary": "0.0.5"
    },
    "devDependencies": {
        "nodeunit": "~0.7.4",
        "grunt-contrib-jshint": "~0.1.0",
        "grunt-contrib-nodeunit": "~0.1.1",
        "libyaml": "~0.2.1",
        "grunt-contrib-clean": "~0.5.0",
        "rimraf": "~2.2.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
