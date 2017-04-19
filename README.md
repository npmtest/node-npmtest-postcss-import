# npmtest-postcss-import

#### test coverage for  [postcss-import (v9.1.0)](https://github.com/postcss/postcss-import#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-import.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-import) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-import.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-import)

#### PostCSS plugin to import CSS files

[![NPM](https://nodei.co/npm/postcss-import.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-import)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-import/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-import/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-import/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-import/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-import/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-import/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-import/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-import/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-import/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-import/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-import/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-import/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-import/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-import/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-import/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-import/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-import/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-import/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maxime Thirouin"
    },
    "bugs": {
        "url": "https://github.com/postcss/postcss-import/issues"
    },
    "dependencies": {
        "object-assign": "^4.0.1",
        "postcss": "^5.0.14",
        "postcss-value-parser": "^3.2.3",
        "promise-each": "^2.2.0",
        "read-cache": "^1.0.0",
        "resolve": "^1.1.7"
    },
    "description": "PostCSS plugin to import CSS files",
    "devDependencies": {
        "ava": "^0.16.0",
        "eslint": "^1.10.3",
        "eslint-config-i-am-meticulous": "^2.0.0",
        "npmpub": "^3.0.1",
        "postcss-scss": "^0.1.3",
        "sugarss": "^0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "95fe9876a1e79af49fbdc3589f01fe5aa7cc1e80",
        "tarball": "https://registry.npmjs.org/postcss-import/-/postcss-import-9.1.0.tgz"
    },
    "eslintConfig": {
        "extends": "eslint-config-i-am-meticulous/es5"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "2a687f867ba73e51aa9a838fa3f14e08174786f7",
    "homepage": "https://github.com/postcss/postcss-import#readme",
    "jspm": {
        "name": "postcss-import",
        "main": "index.js",
        "browser": {
            "./lib/load-content": "@empty",
            "./lib/resolve-id": "@empty"
        }
    },
    "keywords": [
        "css",
        "postcss",
        "postcss-plugin",
        "import",
        "node modules",
        "npm"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "moox"
        },
        {
            "name": "ryanzim"
        },
        {
            "name": "trysound"
        }
    ],
    "name": "postcss-import",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/postcss/postcss-import.git"
    },
    "scripts": {
        "lint": "eslint --fix .",
        "pretest": "npm run lint",
        "release": "npmpub",
        "test": "ava"
    },
    "version": "9.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
