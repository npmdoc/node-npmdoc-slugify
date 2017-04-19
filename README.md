# npmdoc-slugify

#### api documentation for  [slugify (v1.1.0)](https://github.com/simov/slugify)  [![npm package](https://img.shields.io/npm/v/npmdoc-slugify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-slugify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-slugify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-slugify)

#### Slugifies a string

[![NPM](https://nodei.co/npm/slugify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slugify)

- [https://npmdoc.github.io/node-npmdoc-slugify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slugify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slugify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slugify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-slugify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-slugify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simeon Velichkov",
        "url": "http://simov.github.io"
    },
    "bugs": {
        "url": "https://github.com/simov/slugify/issues"
    },
    "dependencies": {},
    "description": "Slugifies a string",
    "devDependencies": {
        "coveralls": "^2.11.15",
        "eslint": "^3.12.2",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7e5b0938d52b5efab1878247ef0f6a4f05db7ee0",
        "tarball": "https://registry.npmjs.org/slugify/-/slugify-1.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "da072f844fd101997d7dd9b65d13a02ea968d893",
    "homepage": "https://github.com/simov/slugify",
    "keywords": [
        "slugify",
        "slug",
        "url",
        "urlify"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "simov"
        }
    ],
    "name": "slugify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/simov/slugify.git"
    },
    "scripts": {
        "lint": "eslint **/*.js && echo Lint Passed",
        "test": "npm run lint && npm run test-ci && echo Tests Passed",
        "test-ci": "mocha",
        "test-cov": "istanbul cover _mocha"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
