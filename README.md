# api documentation for  [phonegap (v6.4.8)](http://github.com/phonegap/phonegap-cli)  [![npm package](https://img.shields.io/npm/v/npmdoc-phonegap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-phonegap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-phonegap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-phonegap)
#### PhoneGap command-line interface and node.js library.

[![NPM](https://nodei.co/npm/phonegap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phonegap)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phonegap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phonegap/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-phonegap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-phonegap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "phonegap",
    "description": "PhoneGap command-line interface and node.js library.",
    "version": "6.4.8",
    "license": "Apache-2.0",
    "homepage": "http://github.com/phonegap/phonegap-cli",
    "repository": {
        "type": "git",
        "url": "git://github.com/phonegap/phonegap-cli.git"
    },
    "keywords": [
        "cli",
        "cordova",
        "phonegap",
        "phonegap build",
        "phonegap/build"
    ],
    "preferGlobal": true,
    "main": "./lib/main.js",
    "bin": {
        "phonegap": "./bin/phonegap.js"
    },
    "scripts": {
        "test": "node node_modules/jasmine-node/bin/jasmine-node --color spec; node_modules/eslint/bin/eslint.js ./ --ignore-path .gitignore",
        "cover": "istanbul cover --print detail -x **/spec/** node_modules/jasmine-node/bin/jasmine-node -- --color spec"
    },
    "engineStrict": true,
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "archiver": "^1.0.0",
        "colors": "0.6.0-1",
        "connect-phonegap": "0.24.5",
        "cordova": "6.4.0",
        "insight": "0.8.2",
        "configstore": "1.4.0",
        "os-name": "2.0.1",
        "minimist": "0.1.0",
        "opener": "1.4.1",
        "opn": "^4.0.2",
        "phonegap-build": "0.10.0",
        "pluralize": "0.0.4",
        "prompt": "0.2.11",
        "qrcode-terminal": "0.9.4",
        "request": "2.81.0",
        "semver": "1.1.0",
        "shelljs": "0.1.4",
        "update-notifier": "^0.6.0"
    },
    "devDependencies": {
        "chdir": "0.0.x",
        "eslint": "^3.12.2",
        "jasmine-node": "1.14.5",
        "istanbul": "0.4.5"
    },
    "optionalDependencies": {},
    "contributors": [
        {
            "name": "Michael Brooks",
            "url": "http://michaelbrooks.ca/"
        },
        {
            "name": "Lorin Beer",
            "url": "http://www.ensufire.com/"
        },
        {
            "name": "Jesse MacFadyen",
            "url": "http://risingj.com"
        },
        {
            "name": "Ryan Stewart"
        },
        {
            "name": "Herm Wong"
        },
        {
            "name": "Suraj Pindoria"
        },
        {
            "name": "Tommy-Carlos Williams"
        }
    ],
    "templates": {
        "blank": {
            "description": "A blank and empty PhoneGap app.",
            "npm": "phonegap-template-blank"
        },
        "csdk-image-editor": {
            "description": "A template for using the Creative Cloud Image Editor.",
            "npm": "phonegap-template-csdk-image-editor"
        },
        "hello-world": {
            "description": "Default hello world app for PhoneGap.",
            "npm": "phonegap-template-hello-world"
        },
        "framework7": {
            "description": "Starter PhoneGap project for Framework7.",
            "npm": "phonegap-template-framework7"
        },
        "push": {
            "description": "An example app for getting started with push notifications",
            "npm": "phonegap-template-push"
        },
        "react-hot-loader": {
            "description": "Starter PhoneGap project using React.js, Babel, Webpack and Hot Reloading.",
            "npm": "phonegap-template-react-hot-loader"
        },
        "star-track": {
            "description": "An example app using Framework7 and the Spotify API.",
            "npm": "phonegap-app-star-track"
        },
        "webvr": {
            "description": "A WebVR and Google Cardboard demo ported from borismus/webvr-boilerplate.",
            "npm": "phonegap-template-webvr"
        },
        "wikitude-augmented-reality": {
            "description": "Augmented Reality demo app powered by the Wikitude plugin",
            "npm": "phonegap-app-augmented-reality"
        }
    },
    "gitHead": "8786fb473ad88ae8d98c30036537b8e230ae84cd",
    "bugs": {
        "url": "https://github.com/phonegap/phonegap-cli/issues"
    },
    "dist": {
        "shasum": "46cb4bfe315b326695d096c0c779cafc63edb03b",
        "tarball": "https://registry.npmjs.org/phonegap/-/phonegap-6.4.8.tgz"
    },
    "maintainers": [
        {
            "name": "devgeeks"
        },
        {
            "name": "filmaj"
        },
        {
            "name": "hermwong"
        },
        {
            "name": "macdonst"
        },
        {
            "name": "mwbrooks"
        },
        {
            "name": "stevegill"
        },
        {
            "name": "surajpindoria"
        },
        {
            "name": "timkim"
        }
    ],
    "directories": {}
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module phonegap](#apidoc.module.phonegap)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>app ()](#apidoc.element.phonegap.app)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>cordova ()](#apidoc.element.phonegap.cordova)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>create ()](#apidoc.element.phonegap.create)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>mode ()](#apidoc.element.phonegap.mode)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>push ()](#apidoc.element.phonegap.push)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>serve ()](#apidoc.element.phonegap.serve)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>share ()](#apidoc.element.phonegap.share)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>version ()](#apidoc.element.phonegap.version)
1.  number <span class="apidocSignatureSpan">phonegap.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">phonegap.</span>_events
1.  object <span class="apidocSignatureSpan">phonegap.</span>util

#### [module phonegap._events](#apidoc.module.phonegap._events)
1.  [function <span class="apidocSignatureSpan">phonegap._events.</span>error (e)](#apidoc.element.phonegap._events.error)



# <a name="apidoc.module.phonegap"></a>[module phonegap](#apidoc.module.phonegap)

#### <a name="apidoc.element.phonegap.app"></a>[function <span class="apidocSignatureSpan">phonegap.</span>app ()](#apidoc.element.phonegap.app)
- description and source-code
```javascript
app = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.cordova"></a>[function <span class="apidocSignatureSpan">phonegap.</span>cordova ()](#apidoc.element.phonegap.cordova)
- description and source-code
```javascript
cordova = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.create"></a>[function <span class="apidocSignatureSpan">phonegap.</span>create ()](#apidoc.element.phonegap.create)
- description and source-code
```javascript
create = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.mode"></a>[function <span class="apidocSignatureSpan">phonegap.</span>mode ()](#apidoc.element.phonegap.mode)
- description and source-code
```javascript
mode = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.push"></a>[function <span class="apidocSignatureSpan">phonegap.</span>push ()](#apidoc.element.phonegap.push)
- description and source-code
```javascript
push = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.serve"></a>[function <span class="apidocSignatureSpan">phonegap.</span>serve ()](#apidoc.element.phonegap.serve)
- description and source-code
```javascript
serve = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.share"></a>[function <span class="apidocSignatureSpan">phonegap.</span>share ()](#apidoc.element.phonegap.share)
- description and source-code
```javascript
share = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.version"></a>[function <span class="apidocSignatureSpan">phonegap.</span>version ()](#apidoc.element.phonegap.version)
- description and source-code
```javascript
version = function () {
    return self.run.apply(self, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phonegap._events"></a>[module phonegap._events](#apidoc.module.phonegap._events)

#### <a name="apidoc.element.phonegap._events.error"></a>[function <span class="apidocSignatureSpan">phonegap._events.</span>error (e)](#apidoc.element.phonegap._events.error)
- description and source-code
```javascript
error = function (e) {}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
