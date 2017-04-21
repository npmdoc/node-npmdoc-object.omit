# npmdoc-object.omit

#### api documentation for  [object.omit (v2.0.1)](https://github.com/jonschlinkert/object.omit)  [![npm package](https://img.shields.io/npm/v/npmdoc-object.omit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-object.omit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-object.omit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-object.omit)

#### Return a copy of an object excluding the given key, or array of keys. Also accepts an optional filter function as the last argument.

[![NPM](https://nodei.co/npm/object.omit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/object.omit)

- [https://npmdoc.github.io/node-npmdoc-object.omit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-object.omit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-object.omit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-object.omit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-object.omit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-object.omit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "object.omit",
    "description": "Return a copy of an object excluding the given key, or array of keys. Also accepts an optional filter function as the last argument.",
    "version": "2.0.1",
    "homepage": "https://github.com/jonschlinkert/object.omit",
    "author": "Jon Schlinkert (https://github.com/jonschlinkert)",
    "repository": "jonschlinkert/object.omit",
    "bugs": {
        "url": "https://github.com/jonschlinkert/object.omit/issues"
    },
    "license": "MIT",
    "files": [
        "index.js"
    ],
    "main": "index.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "dependencies": {
        "for-own": "^0.1.4",
        "is-extendable": "^0.1.1"
    },
    "devDependencies": {
        "gulp-format-md": "^0.1.11",
        "mocha": "^3.1.2",
        "should": "^11.1.1"
    },
    "keywords": [
        "clear",
        "delete",
        "key",
        "object",
        "omit",
        "property",
        "remove",
        "value"
    ],
    "verb": {
        "related": {
            "list": [
                "object.defaults",
                "object.filter",
                "object.pick",
                "object.pluck",
                "object.reduce"
            ]
        },
        "toc": false,
        "layout": "default",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "lint": {
            "reflinks": true
        },
        "reflinks": [
            "verb",
            "verb-generate-readme"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
