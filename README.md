# api documentation for  [fabric (v1.7.9)](http://fabricjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-fabric.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fabric) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fabric.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fabric)
#### Object model for HTML5 canvas, and SVG-to-canvas parser. Backed by jsdom and node-canvas.

[![NPM](https://nodei.co/npm/fabric.png?downloads=true)](https://www.npmjs.com/package/fabric)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fabric/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-fabric_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fabric/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fabric/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fabric/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juriy Zaytsev",
        "email": "kangax@gmail.com"
    },
    "browser": {
        "canvas": false,
        "fs": false,
        "jsdom": false,
        "xmldom": false
    },
    "bugs": {
        "url": "https://github.com/kangax/fabric.js/issues"
    },
    "contributors": [
        {
            "name": "Andrea Bogazzi",
            "email": "andreabogazzi79@gmail.com"
        }
    ],
    "dependencies": {
        "canvas": "1.6.x",
        "jsdom": "3.x.x",
        "xmldom": "0.1.x"
    },
    "description": "Object model for HTML5 canvas, and SVG-to-canvas parser. Backed by jsdom and node-canvas.",
    "devDependencies": {
        "eslint": "2.x.x",
        "istanbul": "0.4.x",
        "onchange": "^3.0.2",
        "qunit": "0.9.x",
        "uglify-js": "2.7.x"
    },
    "directories": {},
    "dist": {
        "shasum": "37cc8cd28fa64b296bf30fb42d7a1d160618b7c2",
        "tarball": "https://registry.npmjs.org/fabric/-/fabric-1.7.9.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "6e2deabcb3eb2f74285892e75e5b05a2242888d2",
    "homepage": "http://fabricjs.com/",
    "keywords": [
        "canvas",
        "graphic",
        "graphics",
        "SVG",
        "node-canvas",
        "parser",
        "HTML5",
        "object model"
    ],
    "license": "MIT",
    "main": "./dist/fabric.js",
    "maintainers": [
        {
            "name": "asturur",
            "email": "andreabogazzi79@gmail.com"
        },
        {
            "name": "kangax",
            "email": "kangax@gmail.com"
        }
    ],
    "name": "fabric",
    "optionalDependencies": {
        "canvas": "1.6.x",
        "jsdom": "3.x.x",
        "xmldom": "0.1.x"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kangax/fabric.js.git"
    },
    "scripts": {
        "all": "npm run build && npm run test && npm run lint && npm run lint_tests && npm run export_dist_to_site && npm run export_tests_to_site",
        "build": "node build.js modules=ALL exclude=json,gestures",
        "build:watch": "onchange 'src/**/**' 'test/**/**' 'HEADER.js' 'lib/**/**' -- npm run build",
        "build_with_gestures": "node build.js modules=ALL exclude=json",
        "export_dist_to_site": "cp dist/fabric.js ../fabricjs.com/lib/fabric.js && cp -r src HEADER.js lib ../fabricjs.com/build/files/",
        "export_tests_to_site": "cp test/unit/*.js ../fabricjs.com/test/unit",
        "lint": "eslint --config .eslintrc.json src",
        "lint_tests": "eslint test/unit --config .eslintrc_tests",
        "test": "node test.js"
    },
    "version": "1.7.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module fabric](#apidoc.module.fabric)



# <a name="apidoc.module.fabric"></a>[module fabric](#apidoc.module.fabric)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
