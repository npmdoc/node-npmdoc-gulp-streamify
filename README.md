# api documentation for  [gulp-streamify (v1.0.2)](https://github.com/nfroidure/gulp-streamify)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-streamify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-streamify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-streamify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-streamify)
#### Wrap old plugins to support streams.

[![NPM](https://nodei.co/npm/gulp-streamify.png?downloads=true)](https://www.npmjs.com/package/gulp-streamify)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-streamify/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-streamify_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-streamify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-streamify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-streamify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Froidure",
        "url": "http://www.insertafter.com/blog.html"
    },
    "bugs": {
        "url": "https://github.com/nfroidure/gulp-streamify/issues"
    },
    "dependencies": {
        "plexer": "1.0.1"
    },
    "description": "Wrap old plugins to support streams.",
    "devDependencies": {
        "coveralls": "~2.11.4",
        "eslint": "^1.3.1",
        "eslint-config-simplifield": "^1.1.0",
        "gulp-util": "~3.0.6",
        "istanbul": "~0.3.19",
        "mocha": "~2.3.1",
        "mocha-lcov-reporter": "0.0.2",
        "sf-lint": "^1.0.2",
        "streamtest": "^1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "00d6b3814d486c088f78738ed0766abc16389e4d",
        "tarball": "https://registry.npmjs.org/gulp-streamify/-/gulp-streamify-1.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "acf97a64b8988f6d90bf6917a11e4bbff769129b",
    "homepage": "https://github.com/nfroidure/gulp-streamify",
    "keywords": [
        "gulpplugin",
        "gulp",
        "gulp-plugin",
        "stream",
        "wrapper"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/nfroidure/gulp-streamify/blob/master/LICENSE"
        }
    ],
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "nfroidure",
            "email": "nfroidure@elitwork.com"
        }
    ],
    "name": "gulp-streamify",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nfroidure/gulp-streamify.git"
    },
    "scripts": {
        "cli": "env NPM_RUN_CLI=1",
        "cover": "istanbul cover --report html _mocha -- tests/*.mocha.js -R spec -t 5000",
        "coveralls": "istanbul cover _mocha --report lcovonly -- tests/*.mocha.js -R spec -t 5000 && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "lint": "eslint **/*.js",
        "prepublish": "npm test && npm run lint",
        "test": "mocha tests/*.mocha.js",
        "trinita": "npm-check-updates -u && npm test && git commit package.json -m \"Dependencies update\" && git push"
    },
    "version": "1.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-streamify](#apidoc.module.gulp-streamify)



# <a name="apidoc.module.gulp-streamify"></a>[module gulp-streamify](#apidoc.module.gulp-streamify)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
