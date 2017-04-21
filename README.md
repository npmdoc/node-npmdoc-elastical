# npmdoc-elastical

#### api documentation for  [elastical (v0.0.13)](https://github.com/ramv/node-elastical/)  [![npm package](https://img.shields.io/npm/v/npmdoc-elastical.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-elastical) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-elastical.svg)](https://travis-ci.org/npmdoc/node-npmdoc-elastical)

#### An ElasticSearch client.

[![NPM](https://nodei.co/npm/elastical.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elastical)

- [https://npmdoc.github.io/node-npmdoc-elastical/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elastical/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elastical/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elastical/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-elastical/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-elastical/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "elastical",
    "description": "An ElasticSearch client.",
    "version": "0.0.13",
    "homepage": "https://github.com/ramv/node-elastical/",
    "author": "Ryan Grove <ryan@wonko.com> (http://wonko.com/)",
    "copyright": "Copyright (c) 2013 Ryan Grove. All rights reserved.",
    "keywords": [
        "elasticsearch",
        "elastic",
        "search",
        "client",
        "lucene"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/ramv/node-elastical/blob/master/LICENSE.md"
        }
    ],
    "repository": [
        {
            "type": "git",
            "url": "git://github.com/ramv/node-elastical.git"
        }
    ],
    "engines": [
        "node >=0.4.0",
        "npm >=1.0.0"
    ],
    "dependencies": {
        "request": ">=2.9.200",
        "diff": ">=1.0.3"
    },
    "devDependencies": {
        "vows": "*"
    },
    "main": "index",
    "scripts": {
        "test": "node_modules/.bin/vows tests/offline-tests.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
