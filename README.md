# api documentation for  [mongo-querystring (v4.1.0)](https://github.com/Turistforeningen/node-mongo-querystring#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongo-querystring.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongo-querystring) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongo-querystring.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongo-querystring)
#### Parse and pass URL queries to MongoDB query

[![NPM](https://nodei.co/npm/mongo-querystring.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongo-querystring)

- [https://npmdoc.github.io/node-npmdoc-mongo-querystring/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongo-querystring/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongo-querystring/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongo-querystring/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongo-querystring/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongo-querystring/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hans Kristian Flaatten"
    },
    "bugs": {
        "url": "https://github.com/Turistforeningen/node-mongo-querystring/issues"
    },
    "dependencies": {},
    "description": "Parse and pass URL queries to MongoDB query",
    "devDependencies": {
        "JSONStream": "^1.1.1",
        "codacy-coverage": "^2.0.0",
        "eslint": "^3.1.1",
        "eslint-config-airbnb-base": "^10.0.1",
        "eslint-plugin-import": "^2.2.0",
        "express": "^4.13.4",
        "greenkeeper-postpublish": "^1.0.0",
        "istanbul": "^0.4.3",
        "mocha": "^3.0.0",
        "mongodb": "^2.1.18",
        "nsp": "^2.4.0",
        "qs": "^6.2.0",
        "semantic-release": "^4.3.5",
        "supertest": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "03015e793e8b15eb1da833fd21d2935a1f997776",
        "tarball": "https://registry.npmjs.org/mongo-querystring/-/mongo-querystring-4.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "index.js",
        "examples",
        "test.js"
    ],
    "gitHead": "c8e68a89217ebc174cf2b0bf0014772715db41fa",
    "homepage": "https://github.com/Turistforeningen/node-mongo-querystring#readme",
    "keywords": [
        "query",
        "querystring",
        "parser",
        "uri",
        "url",
        "mongo",
        "mongodb"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "turistforeningen"
        }
    ],
    "name": "mongo-querystring",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Turistforeningen/node-mongo-querystring.git"
    },
    "scripts": {
        "codacy-coverage": "codacy-coverage",
        "cover": "istanbul cover --report lcovonly ./node_modules/.bin/_mocha -- -R spec test.js examples/test.js",
        "greenkeeper-postpublish": "greenkeeper-postpublish",
        "grunt:watch": "grunt watch",
        "lint": "eslint index.js test.js examples",
        "nsp": "nsp check",
        "semantic-release": "semantic-release",
        "test": "mocha -c -b --check-leaks -R tap test.js examples/test.js",
        "test:watch": "mocha -w -c -b --check-leaks -R progress test.js examples/test.js"
    },
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
