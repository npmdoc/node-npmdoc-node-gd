# npmdoc-node-gd

#### api documentation for  [node-gd (v1.5.0)](https://github.com/y-a-v-a/node-gd)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-gd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-gd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-gd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-gd)

#### GD graphics library (libgd) C++ bindings for Node.js

[![NPM](https://nodei.co/npm/node-gd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gd)

- [https://npmdoc.github.io/node-npmdoc-node-gd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-gd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-gd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-gd",
    "version": "1.5.0",
    "description": "GD graphics library (libgd) C++ bindings for Node.js",
    "main": "js/node-gd.js",
    "directories": {
        "test": "test"
    },
    "os": [
        "!win32"
    ],
    "homepage": "https://github.com/y-a-v-a/node-gd",
    "bugs": "https://github.com/y-a-v-a/node-gd/issues",
    "scripts": {
        "pretest": "node-gyp rebuild",
        "test": "mocha --expose-gc --reporter spec --bail --ui bdd --colors",
        "install": "node-gyp rebuild",
        "update-contributors": "git shortlog -s -e -n>CONTRIBUTORS.md"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/y-a-v-a/node-gd.git"
    },
    "keywords": [
        "libgd",
        "libgd2",
        "gd",
        "image",
        "png",
        "jpg",
        "jpeg",
        "gif",
        "graphics",
        "library"
    ],
    "author": "Taegon Kim <gonom9@gmail.com>",
    "license": "MIT",
    "contributors": [
        {
            "name": "Dudochkin Victor"
        },
        {
            "name": "Andris Reinman"
        },
        {
            "name": "Peter Magnusson"
        },
        {
            "name": "Damian Senn"
        },
        {
            "name": "Farrin Reid"
        },
        {
            "name": "Josh (zer0x304)"
        },
        {
            "name": "Mike Smullin"
        },
        {
            "name": "Vincent Bruijn (y_a_v_a)"
        }
    ],
    "gypfile": true,
    "readmeFilename": "README.md",
    "devDependencies": {
        "chai": "3.5.0",
        "mocha": "2.4.5"
    },
    "dependencies": {
        "node-gyp": "3.6.0",
        "nan": "2.5.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
