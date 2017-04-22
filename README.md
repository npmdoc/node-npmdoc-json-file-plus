# npmdoc-json-file-plus

#### api documentation for  [json-file-plus (v3.3.0)](https://github.com/ljharb/json-file-plus#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-json-file-plus.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-json-file-plus) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-json-file-plus.svg)](https://travis-ci.org/npmdoc/node-npmdoc-json-file-plus)

#### Read from and write to a JSON file, minimizing diffs and preserving formatting.

[![NPM](https://nodei.co/npm/json-file-plus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-file-plus)

- [https://npmdoc.github.io/node-npmdoc-json-file-plus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jordan Harband",
        "url": "http://ljharb.codes"
    },
    "bugs": {
        "url": "https://github.com/ljharb/json-file-plus/issues"
    },
    "contributors": [
        {
            "name": "Jordan Harband",
            "url": "http://ljharb.codes"
        }
    ],
    "dependencies": {
        "is": "^3.1.0",
        "node.extend": "^1.1.5",
        "promiseback": "^2.0.2"
    },
    "description": "Read from and write to a JSON file, minimizing diffs and preserving formatting.",
    "devDependencies": {
        "@ljharb/eslint-config": "^2.1.1",
        "covert": "^1.1.0",
        "eslint": "^2.4.0",
        "evalmd": "^0.0.16",
        "foreach": "^2.0.5",
        "jscs": "^2.11.0",
        "nsp": "^2.2.1",
        "object-keys": "^1.0.9",
        "tape": "^4.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "702a0bcaff6d85c0edbe1cd03c88a582532f99f5",
        "tarball": "https://registry.npmjs.org/json-file-plus/-/json-file-plus-3.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.4"
    },
    "gitHead": "a2156788085402c0594fd9f6bdc04fe37ccc1c6b",
    "homepage": "https://github.com/ljharb/json-file-plus#readme",
    "keywords": [
        "json",
        "json file",
        "formatting",
        "read",
        "write",
        "promise",
        "promiseback"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ljharb"
        }
    ],
    "name": "json-file-plus",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ljharb/json-file-plus.git"
    },
    "scripts": {
        "coverage": "covert test/test.js",
        "coverage-quiet": "covert test/test.js --quiet",
        "eslint": "eslint *.js test/*.js",
        "jscs": "jscs *.js test/*.js",
        "lint": "npm run jscs && npm run eslint",
        "posttest": "npm run --silent security",
        "pretest": "npm run --silent lint && evalmd README.md",
        "security": "nsp check",
        "test": "npm run tests-only",
        "tests-only": "node test/test.js"
    },
    "version": "3.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
