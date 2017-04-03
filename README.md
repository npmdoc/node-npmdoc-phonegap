# api documentation for  [phonegap (v6.4.6)](http://github.com/phonegap/phonegap-cli)  [![npm package](https://img.shields.io/npm/v/npmdoc-phonegap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-phonegap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-phonegap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-phonegap)
#### PhoneGap command-line interface and node.js library.

[![NPM](https://nodei.co/npm/phonegap.png?downloads=true)](https://www.npmjs.com/package/phonegap)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phonegap/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-phonegap_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phonegap/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-phonegap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-phonegap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "phonegap",
    "description": "PhoneGap command-line interface and node.js library.",
    "version": "6.4.6",
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
    "preferGlobal": "true",
    "main": "./lib/main.js",
    "bin": {
        "phonegap": "./bin/phonegap.js"
    },
    "scripts": {
        "test": "node node_modules/jasmine-node/bin/jasmine-node --color spec; node_modules/eslint/bin/eslint.js ./"
    },
    "engineStrict": "true",
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "archiver": "^1.0.0",
        "colors": "0.6.0-1",
        "connect-phonegap": "0.24.5",
        "cordova": "6.4.0",
        "insight": "0.8.2",
        "minimist": "0.1.0",
        "opener": "1.4.1",
        "opn": "^4.0.2",
        "phonegap-build": "0.10.0",
        "pluralize": "0.0.4",
        "prompt": "0.2.11",
        "qrcode-terminal": "0.9.4",
        "semver": "1.1.0",
        "shelljs": "0.1.4",
        "update-notifier": "^0.6.0"
    },
    "devDependencies": {
        "chdir": "0.0.x",
        "eslint": "^3.12.2",
        "jasmine-node": "1.14.5"
    },
    "optionalDependencies": {},
    "contributors": [
        {
            "name": "Michael Brooks",
            "email": "michael@michaelbrooks.ca",
            "url": "http://michaelbrooks.ca/"
        },
        {
            "name": "Lorin Beer",
            "email": "lorin.beer@gmail.com",
            "url": "http://www.ensufire.com/"
        },
        {
            "name": "Jesse MacFadyen",
            "url": "http://risingj.com"
        },
        {
            "name": "Ryan Stewart",
            "email": "ryan@adobe.com"
        },
        {
            "name": "Herm Wong",
            "email": "herm.wong@gmail.com"
        },
        {
            "name": "Suraj Pindoria",
            "email": "suraj.pindoria@yahoo.com"
        },
        {
            "name": "Tommy-Carlos Williams",
            "email": "tommy@devgeeks.org"
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
    "gitHead": "a26b4bb47156d1371c4a83756d53d0a0dc8df08c",
    "bugs": {
        "url": "https://github.com/phonegap/phonegap-cli/issues"
    },
    "dist": {
        "shasum": "2000c0412c39401b65cddf4051a39e6eab75280c",
        "tarball": "https://registry.npmjs.org/phonegap/-/phonegap-6.4.6.tgz"
    },
    "maintainers": [
        {
            "name": "devgeeks",
            "email": "tommy@devgeeks.org"
        },
        {
            "name": "hermwong",
            "email": "herm.wong@gmail.com"
        },
        {
            "name": "macdonst",
            "email": "simon.macdonald@gmail.com"
        },
        {
            "name": "mwbrooks",
            "email": "michael@michaelbrooks.ca"
        },
        {
            "name": "stevegill",
            "email": "stevengill97@gmail.com"
        },
        {
            "name": "surajpindoria",
            "email": "suraj.pindoria@yahoo.com"
        },
        {
            "name": "timkim",
            "email": "timk@adobe.com"
        }
    ],
    "directories": {},
    "readme": "ERROR: No README data found!"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module phonegap](#apidoc.module.phonegap)
1.  [function <span class="apidocSignatureSpan"></span>phonegap ()](#apidoc.element.phonegap.phonegap)
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

#### [module phonegap.phonegap](#apidoc.module.phonegap.phonegap)
1.  [function <span class="apidocSignatureSpan">phonegap.</span>phonegap ()](#apidoc.element.phonegap.phonegap.phonegap)
1.  [function <span class="apidocSignatureSpan">phonegap.phonegap.</span>super_ ()](#apidoc.element.phonegap.phonegap.super_)



# <a name="apidoc.module.phonegap"></a>[module phonegap](#apidoc.module.phonegap)

#### <a name="apidoc.element.phonegap.phonegap"></a>[function <span class="apidocSignatureSpan"></span>phonegap ()](#apidoc.element.phonegap.phonegap)
- description and source-code
```javascript
function PhoneGap() {
    // initialize PhoneGap
    initialize.call(this);

    // initialize each command and inject the 'phonegap' dependency.
    this.cordova = require('./phonegap/cordova').create(this);
    this.create = require('./phonegap/create').create(this);
    this.mode = require('./phonegap/mode').create(this);
    this.template.list = require('./phonegap/template.list').create(this);
    this.template.search = require('./phonegap/template.search').create(this);
    this.remote.build = require('./phonegap/remote.build').create(this);
    this.remote.install = require('./phonegap/remote.install').create(this);
    this.remote.login = require('./phonegap/remote.login').create(this);
    this.remote.logout = require('./phonegap/remote.logout').create(this);
    this.remote.run = require('./phonegap/remote.run').create(this);
    this.serve = require('./phonegap/serve').create(this);
    this.app = this.serve;
    this.version = require('./phonegap/version').create(this);
    this.push = require('./phonegap/push').create(this);
    this.share = require('./phonegap/share').create(this);

    // set normal mode (not verbose and not quiet)
    this.mode({ verbose: false });

    // utility methods
    this.util = {};
    this.util.cordova = require('./cordova').cordova;
}
```
- example usage
```shell
n/a
```

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
...
 */

function PhoneGap() {
// initialize PhoneGap
initialize.call(this);

// initialize each command and inject the 'phonegap' dependency.
this.cordova = require('./phonegap/cordova').create(this);
this.create = require('./phonegap/create').create(this);
this.mode = require('./phonegap/mode').create(this);
this.template.list = require('./phonegap/template.list').create(this);
this.template.search = require('./phonegap/template.search').create(this);
this.remote.build = require('./phonegap/remote.build').create(this);
this.remote.install = require('./phonegap/remote.install').create(this);
this.remote.login = require('./phonegap/remote.login').create(this);
...
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
...
    this.serve = require('./phonegap/serve').create(this);
    this.app = this.serve;
    this.version = require('./phonegap/version').create(this);
    this.push = require('./phonegap/push').create(this);
    this.share = require('./phonegap/share').create(this);

    // set normal mode (not verbose and not quiet)
    this.mode({ verbose: false });

    // utility methods
    this.util = {};
    this.util.cordova = require('./cordova').cordova;
}

util.inherits(PhoneGap, events.EventEmitter);
...
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



# <a name="apidoc.module.phonegap.phonegap"></a>[module phonegap.phonegap](#apidoc.module.phonegap.phonegap)

#### <a name="apidoc.element.phonegap.phonegap.phonegap"></a>[function <span class="apidocSignatureSpan">phonegap.</span>phonegap ()](#apidoc.element.phonegap.phonegap.phonegap)
- description and source-code
```javascript
function PhoneGap() {
    // initialize PhoneGap
    initialize.call(this);

    // initialize each command and inject the 'phonegap' dependency.
    this.cordova = require('./phonegap/cordova').create(this);
    this.create = require('./phonegap/create').create(this);
    this.mode = require('./phonegap/mode').create(this);
    this.template.list = require('./phonegap/template.list').create(this);
    this.template.search = require('./phonegap/template.search').create(this);
    this.remote.build = require('./phonegap/remote.build').create(this);
    this.remote.install = require('./phonegap/remote.install').create(this);
    this.remote.login = require('./phonegap/remote.login').create(this);
    this.remote.logout = require('./phonegap/remote.logout').create(this);
    this.remote.run = require('./phonegap/remote.run').create(this);
    this.serve = require('./phonegap/serve').create(this);
    this.app = this.serve;
    this.version = require('./phonegap/version').create(this);
    this.push = require('./phonegap/push').create(this);
    this.share = require('./phonegap/share').create(this);

    // set normal mode (not verbose and not quiet)
    this.mode({ verbose: false });

    // utility methods
    this.util = {};
    this.util.cordova = require('./cordova').cordova;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phonegap.phonegap.super_"></a>[function <span class="apidocSignatureSpan">phonegap.phonegap.</span>super_ ()](#apidoc.element.phonegap.phonegap.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
