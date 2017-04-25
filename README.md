# npmtest-suspend

#### basic test coverage for  [suspend (v0.7.0)](https://github.com/jmar777/suspend#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-suspend.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-suspend) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-suspend.svg)](https://travis-ci.org/npmtest/node-npmtest-suspend)

#### Async control-flow for Node.js using ES6 generators.

[![NPM](https://nodei.co/npm/suspend.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/suspend)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-suspend/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-suspend/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-suspend/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-suspend/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-suspend/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-suspend/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-suspend/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-suspend/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-suspend/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-suspend/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-suspend/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-suspend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-suspend/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-suspend/build/test-report.html](https://npmtest.github.io/node-npmtest-suspend/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-suspend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-suspend/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-suspend/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-suspend/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-suspend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-suspend/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-suspend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-suspend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Martin",
        "url": "http://twitter.com/jmar777"
    },
    "bugs": {
        "url": "https://github.com/jmar777/suspend/issues"
    },
    "dependencies": {
        "promise": "^6.0.0"
    },
    "description": "Async control-flow for Node.js using ES6 generators.",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-contrib-jshint": "^0.10.0",
        "mocha": "^1.21.4",
        "regenerator": "^0.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "e54cdb4724f0dee56c4ba3f382d4d4994e555fa2",
        "tarball": "https://registry.npmjs.org/suspend/-/suspend-0.7.0.tgz"
    },
    "engines": {
        "node": ">=0.11.3"
    },
    "gitHead": "085b4a82c6eb4c3e0d8c4d96484c82bf1cf101cb",
    "homepage": "https://github.com/jmar777/suspend#readme",
    "keywords": [
        "async",
        "generator",
        "yield",
        "callback",
        "promise",
        "flow",
        "control",
        "suspend"
    ],
    "license": "MIT",
    "main": "lib/suspend.js",
    "maintainers": [
        {
            "name": "jmar777"
        }
    ],
    "name": "suspend",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jmar777/suspend.git"
    },
    "scripts": {
        "test": "node ./node_modules/mocha/bin/mocha --harmony --reporter list",
        "test-es5": "node test-es5/run.js"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
