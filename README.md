# npmdoc-eslint

#### api documentation for  [eslint (v3.19.0)](http://eslint.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint)

#### An AST-based pattern checker for JavaScript.

[![NPM](https://nodei.co/npm/eslint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint)

- [https://npmdoc.github.io/node-npmdoc-eslint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicholas C. Zakas"
    },
    "bin": {
        "eslint": "./bin/eslint.js"
    },
    "bugs": {
        "url": "https://github.com/eslint/eslint/issues/"
    },
    "dependencies": {
        "babel-code-frame": "^6.16.0",
        "chalk": "^1.1.3",
        "concat-stream": "^1.5.2",
        "debug": "^2.1.1",
        "doctrine": "^2.0.0",
        "escope": "^3.6.0",
        "espree": "^3.4.0",
        "esquery": "^1.0.0",
        "estraverse": "^4.2.0",
        "esutils": "^2.0.2",
        "file-entry-cache": "^2.0.0",
        "glob": "^7.0.3",
        "globals": "^9.14.0",
        "ignore": "^3.2.0",
        "imurmurhash": "^0.1.4",
        "inquirer": "^0.12.0",
        "is-my-json-valid": "^2.10.0",
        "is-resolvable": "^1.0.0",
        "js-yaml": "^3.5.1",
        "json-stable-stringify": "^1.0.0",
        "levn": "^0.3.0",
        "lodash": "^4.0.0",
        "mkdirp": "^0.5.0",
        "natural-compare": "^1.4.0",
        "optionator": "^0.8.2",
        "path-is-inside": "^1.0.1",
        "pluralize": "^1.2.1",
        "progress": "^1.1.8",
        "require-uncached": "^1.0.2",
        "shelljs": "^0.7.5",
        "strip-bom": "^3.0.0",
        "strip-json-comments": "~2.0.1",
        "table": "^3.7.8",
        "text-table": "~0.2.0",
        "user-home": "^2.0.0"
    },
    "description": "An AST-based pattern checker for JavaScript.",
    "devDependencies": {
        "babel-polyfill": "^6.23.0",
        "babel-preset-es2015": "^6.24.0",
        "babelify": "^7.3.0",
        "beefy": "^2.1.8",
        "brfs": "1.4.3",
        "browserify": "^14.1.0",
        "chai": "^3.5.0",
        "cheerio": "^0.22.0",
        "coveralls": "^2.12.0",
        "dateformat": "^2.0.0",
        "ejs": "^2.5.6",
        "eslint-plugin-eslint-plugin": "^0.7.1",
        "eslint-plugin-node": "^4.2.1",
        "eslint-release": "^0.10.1",
        "esprima": "^3.1.3",
        "esprima-fb": "^15001.1001.0-dev-harmony-fb",
        "istanbul": "^0.4.5",
        "jsdoc": "^3.4.3",
        "karma": "^1.5.0",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.2",
        "karma-phantomjs-launcher": "^1.0.4",
        "leche": "^2.1.2",
        "load-perf": "^0.2.0",
        "markdownlint": "^0.4.0",
        "mocha": "^3.2.0",
        "mock-fs": "^4.2.0",
        "npm-license": "^0.3.3",
        "phantomjs-prebuilt": "^2.1.14",
        "proxyquire": "^1.7.11",
        "semver": "^5.3.0",
        "shelljs-nodecli": "~0.1.1",
        "sinon": "^2.0.0",
        "temp": "^0.8.3",
        "through": "^2.3.8"
    },
    "directories": {},
    "dist": {
        "shasum": "c8fc6201c7f40dd08941b87c085767386a679acc",
        "tarball": "https://registry.npmjs.org/eslint/-/eslint-3.19.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "LICENSE",
        "README.md",
        "bin",
        "conf",
        "lib",
        "messages"
    ],
    "gitHead": "421aab44a9c167c82210bed52f68cf990b7edbea",
    "homepage": "http://eslint.org",
    "keywords": [
        "ast",
        "lint",
        "javascript",
        "ecmascript",
        "espree"
    ],
    "license": "MIT",
    "main": "./lib/api.js",
    "maintainers": [
        {
            "name": "eslint"
        },
        {
            "name": "ivolodin"
        },
        {
            "name": "nzakas"
        }
    ],
    "name": "eslint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eslint/eslint.git"
    },
    "scripts": {
        "alpharelease": "node Makefile.js prerelease -- alpha",
        "betarelease": "node Makefile.js prerelease -- beta",
        "browserify": "node Makefile.js browserify",
        "check-commit": "node Makefile.js checkGitCommit",
        "ci-release": "node Makefile.js ciRelease",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "docs": "node Makefile.js docs",
        "gensite": "node Makefile.js gensite",
        "lint": "node Makefile.js lint",
        "perf": "node Makefile.js perf",
        "profile": "beefy tests/bench/bench.js --open -- -t brfs -t ./tests/bench/xform-rules.js -r espree",
        "release": "node Makefile.js release",
        "test": "node Makefile.js test"
    },
    "version": "3.19.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
