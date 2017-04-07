# api documentation for  [sync-request (v4.0.1)](https://github.com/ForbesLindesay/sync-request#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sync-request.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sync-request) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sync-request.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sync-request)
#### Make synchronous web requests

[![NPM](https://nodei.co/npm/sync-request.png?downloads=true)](https://www.npmjs.com/package/sync-request)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sync-request/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sync-request_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sync-request/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sync-request/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sync-request/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ForbesLindesay"
    },
    "browser": "./browser.js",
    "bugs": {
        "url": "https://github.com/ForbesLindesay/sync-request/issues"
    },
    "dependencies": {
        "concat-stream": "^1.4.7",
        "get-port": "^2.1.0",
        "http-response-object": "^1.0.1",
        "then-request": "^2.0.1"
    },
    "description": "Make synchronous web requests",
    "devDependencies": {
        "body-parser": "^1.14.1",
        "express": "^4.13.3",
        "morgan": "^1.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a49653f17d9f68b554b6c76bd8000da086014411",
        "tarball": "https://registry.npmjs.org/sync-request/-/sync-request-4.0.1.tgz"
    },
    "gitHead": "c5ece602b9ddd53e507b01f21299eedc96129070",
    "homepage": "https://github.com/ForbesLindesay/sync-request#readme",
    "keywords": [
        "request",
        "http",
        "https",
        "cache",
        "browserify",
        "synchronous",
        "sync"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "forbeslindesay",
            "email": "forbes@lindeay.co.uk"
        }
    ],
    "name": "sync-request",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ForbesLindesay/sync-request.git"
    },
    "scripts": {
        "test": "node test && node test --legacy && node test/benchmark"
    },
    "version": "4.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sync-request](#apidoc.module.sync-request)
1.  [function <span class="apidocSignatureSpan">sync-request.</span>legacyRequest (method, url, options)](#apidoc.element.sync-request.legacyRequest)



# <a name="apidoc.module.sync-request"></a>[module sync-request](#apidoc.module.sync-request)

#### <a name="apidoc.element.sync-request.legacyRequest"></a>[function <span class="apidocSignatureSpan">sync-request.</span>legacyRequest (method, url, options)](#apidoc.element.sync-request.legacyRequest)
- description and source-code
```javascript
function legacyRequest(method, url, options) {
  return doRequestWith(process.execPath, [require.resolve('./lib/legacy-worker')], method, url, options);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
