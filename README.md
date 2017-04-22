# npmtest-eslint-plugin-lodash

#### basic test coverage for  [eslint-plugin-lodash (v2.4.0)](https://github.com/wix/eslint-plugin-lodash)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-lodash.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-lodash) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-lodash.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-lodash)

#### Lodash specific linting rules for ESLint

[![NPM](https://nodei.co/npm/eslint-plugin-lodash.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-lodash)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-lodash/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-lodash/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Omer Ganim"
    },
    "bugs": {
        "url": "https://github.com/wix/eslint-plugin-lodash/issues"
    },
    "dependencies": {
        "lodash": "~4.17.0"
    },
    "description": "Lodash specific linting rules for ESLint",
    "devDependencies": {
        "babel-cli": "6.16.0",
        "babel-plugin-istanbul": "2.0.3",
        "babel-preset-es2015": "6.16.0",
        "babel-register": "6.16.3",
        "coveralls": "^2.11.11",
        "cross-env": "3.1.3",
        "eslint": "3.7.1",
        "eslint-config-wix-editor": "0.2.3",
        "eslint-traverser": "1.5.2",
        "istanbul": "^0.4.4",
        "mocha": "3.1.0",
        "nyc": "8.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0506195942e948883dea818ec0bcddee9cc2894a",
        "tarball": "https://registry.npmjs.org/eslint-plugin-lodash/-/eslint-plugin-lodash-2.4.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "files": [
        "LICENSE",
        "README.md",
        "lib"
    ],
    "gitHead": "57b83c05db65d601723fe3e73ef32dd0e1e700fd",
    "homepage": "https://github.com/wix/eslint-plugin-lodash",
    "keywords": [
        "eslint",
        "eslint-plugin",
        "eslintplugin",
        "lodash"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "danyshaanan"
        },
        {
            "name": "ganimomer"
        },
        {
            "name": "idok"
        }
    ],
    "name": "eslint-plugin-lodash",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": ">=2.10.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wix/eslint-plugin-lodash.git"
    },
    "scripts": {
        "build": "babel src -d lib",
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "lint": "eslint ./",
        "prepublish": "npm run build",
        "test": "npm run lint && npm run unit-test",
        "unit-test": "cross-env NODE_ENV=test nyc mocha tests/**/*.js --reporter=dot"
    },
    "version": "2.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
