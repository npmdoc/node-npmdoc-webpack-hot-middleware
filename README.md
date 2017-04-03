# api documentation for  [webpack-hot-middleware (v2.18.0)](https://github.com/glenjamin/webpack-hot-middleware#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-webpack-hot-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-webpack-hot-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-webpack-hot-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-webpack-hot-middleware)
#### Webpack hot reloading you can attach to your own server

[![NPM](https://nodei.co/npm/webpack-hot-middleware.png?downloads=true)](https://www.npmjs.com/package/webpack-hot-middleware)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-hot-middleware/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-webpack-hot-middleware_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-hot-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-webpack-hot-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-webpack-hot-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Glen Mailer",
        "email": "glen@stainlessed.co.uk"
    },
    "bugs": {
        "url": "https://github.com/glenjamin/webpack-hot-middleware/issues"
    },
    "dependencies": {
        "ansi-html": "0.0.7",
        "html-entities": "^1.2.0",
        "querystring": "^0.2.0",
        "strip-ansi": "^3.0.0"
    },
    "description": "Webpack hot reloading you can attach to your own server",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "express": "^4.13.3",
        "istanbul": "^0.4.2",
        "mocha": "^2.3.2",
        "sinon": "^1.12.2",
        "supertest": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a16bb535b83a6ac94a78ac5ebce4f3059e8274d3",
        "tarball": "https://registry.npmjs.org/webpack-hot-middleware/-/webpack-hot-middleware-2.18.0.tgz"
    },
    "gitHead": "7d2db1378cde3e3bc111e10d5cb3e463595e68e8",
    "homepage": "https://github.com/glenjamin/webpack-hot-middleware#readme",
    "keywords": [
        "webpack",
        "hmr",
        "hot",
        "module",
        "reloading",
        "hot-reloading",
        "middleware",
        "express"
    ],
    "license": "MIT",
    "main": "middleware.js",
    "maintainers": [
        {
            "name": "glenjamin",
            "email": "glenjamin@gmail.com"
        }
    ],
    "name": "webpack-hot-middleware",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/glenjamin/webpack-hot-middleware.git"
    },
    "scripts": {
        "test": "mocha",
        "travis": "istanbul cover _mocha --"
    },
    "version": "2.18.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module webpack-hot-middleware](#apidoc.module.webpack-hot-middleware)
1.  object <span class="apidocSignatureSpan">webpack-hot-middleware.</span>helpers

#### [module webpack-hot-middleware.helpers](#apidoc.module.webpack-hot-middleware.helpers)
1.  [function <span class="apidocSignatureSpan">webpack-hot-middleware.helpers.</span>pathMatch (url, path)](#apidoc.element.webpack-hot-middleware.helpers.pathMatch)



# <a name="apidoc.module.webpack-hot-middleware"></a>[module webpack-hot-middleware](#apidoc.module.webpack-hot-middleware)



# <a name="apidoc.module.webpack-hot-middleware.helpers"></a>[module webpack-hot-middleware.helpers](#apidoc.module.webpack-hot-middleware.helpers)

#### <a name="apidoc.element.webpack-hot-middleware.helpers.pathMatch"></a>[function <span class="apidocSignatureSpan">webpack-hot-middleware.helpers.</span>pathMatch (url, path)](#apidoc.element.webpack-hot-middleware.helpers.pathMatch)
- description and source-code
```javascript
function pathMatch(url, path) {
  if (url == path) return true;
  var q = url.indexOf('?');
  if (q == -1) return false;
  return url.substring(0, q) == path;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
