# npmtest-copy-webpack-plugin

#### test coverage for  [copy-webpack-plugin (v4.0.1)](https://github.com/kevlened/copy-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-copy-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-copy-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-copy-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-copy-webpack-plugin)

#### Copy files and directories in webpack

[![NPM](https://nodei.co/npm/copy-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/copy-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-copy-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-copy-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-copy-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-copy-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-copy-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-copy-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-copy-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Len Boyette"
    },
    "bugs": {
        "url": "https://github.com/kevlened/copy-webpack-plugin/issues"
    },
    "dependencies": {
        "bluebird": "^2.10.2",
        "fs-extra": "^0.26.4",
        "glob": "^6.0.4",
        "is-glob": "^3.1.0",
        "loader-utils": "^0.2.15",
        "lodash": "^4.3.0",
        "minimatch": "^3.0.0",
        "node-dir": "^0.1.10"
    },
    "description": "Copy files and directories in webpack",
    "devDependencies": {
        "babel-cli": "^6.8.0",
        "babel-preset-es2015": "^6.6.0",
        "chai": "^3.4.0",
        "eslint": "^2.9.0",
        "mocha": "^2.4.5",
        "ncp": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9728e383b94316050d0c7463958f2b85c0aa8200",
        "tarball": "https://registry.npmjs.org/copy-webpack-plugin/-/copy-webpack-plugin-4.0.1.tgz"
    },
    "gitHead": "de4ff3231646548e9b524cde45cc1655cbb3373d",
    "homepage": "https://github.com/kevlened/copy-webpack-plugin",
    "keywords": [
        "webpack",
        "plugin",
        "transfer",
        "move",
        "copy"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "kevlened"
        }
    ],
    "name": "copy-webpack-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kevlened/copy-webpack-plugin.git"
    },
    "scripts": {
        "build": "babel src/ --out-dir dist/",
        "build:tests": "babel tests/ --out-dir compiled_tests/ && ncp tests/helpers compiled_tests/helpers",
        "lint": "eslint src/ tests/",
        "pretest": "npm run lint && npm run build && npm run build:tests",
        "test": "mocha compiled_tests/",
        "test:nolint": "npm run build && npm run build:tests && mocha compiled_tests/"
    },
    "version": "4.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
