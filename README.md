# npmdoc-browserify-ngannotate

#### basic api documentation for  [browserify-ngannotate (v2.0.0)](https://github.com/omsmith/browserify-ngannotate)  [![npm package](https://img.shields.io/npm/v/npmdoc-browserify-ngannotate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browserify-ngannotate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browserify-ngannotate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browserify-ngannotate)

#### A browserify transform that uses ng-annotate to add dependency injection annotations to your AngularJS source code, preparing it for minification.

[![NPM](https://nodei.co/npm/browserify-ngannotate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserify-ngannotate)

- [https://npmdoc.github.io/node-npmdoc-browserify-ngannotate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserify-ngannotate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserify-ngannotate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserify-ngannotate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browserify-ngannotate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browserify-ngannotate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Owen Smith",
        "url": "http://omsmith.ca"
    },
    "bugs": {
        "url": "https://github.com/omsmith/browserify-ngannotate/issues"
    },
    "dependencies": {
        "clone": "^1.0.2",
        "defaults": "^1.0.3",
        "ng-annotate": "^1.0.2",
        "through2": "^2.0.0"
    },
    "description": "A browserify transform that uses ng-annotate to add dependency injection annotations to your AngularJS source code, preparing it for minification.",
    "devDependencies": {
        "browserify": "^12.0.1",
        "chai": "^3.4.1",
        "convert-source-map": "^1.1.2",
        "coveralls": "^2.11.4",
        "istanbul": "^0.4.1",
        "mocha": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a67619f07597f1a3eb47484fd87e84bb035d956e",
        "tarball": "https://registry.npmjs.org/browserify-ngannotate/-/browserify-ngannotate-2.0.0.tgz"
    },
    "gitHead": "301236b84e584acdbc29ab2554b8c683ba2d53b7",
    "homepage": "https://github.com/omsmith/browserify-ngannotate",
    "keywords": [
        "browserify",
        "browserify-transform",
        "angular",
        "ng-annotate",
        "annotate",
        "ngmin",
        "ng"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "omsmith"
        },
        {
            "name": "olov"
        }
    ],
    "name": "browserify-ngannotate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/omsmith/browserify-ngannotate.git"
    },
    "scripts": {
        "report-cov": "cat ./coverage/lcov.info | coveralls",
        "test": "istanbul cover -x \"**/spec/**\" _mocha -- -R spec spec"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
