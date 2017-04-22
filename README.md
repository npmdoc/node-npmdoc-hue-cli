# npmdoc-hue-cli

#### api documentation for  hue-cli (v0.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-hue-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hue-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hue-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hue-cli)

#### A command line interface to philips hue

[![NPM](https://nodei.co/npm/hue-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hue-cli)

- [https://npmdoc.github.io/node-npmdoc-hue-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hue-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hue-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hue-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hue-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hue-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hue-cli",
    "description": "A command line interface to philips hue",
    "author": "Dave Eddy <dave@daveeddy.com> (http://www.daveeddy.com)",
    "version": "0.2.0",
    "repository": {
        "url": "https://github.com/bahamas10/hue-cli",
        "type": "git"
    },
    "scripts": {
        "test": "for f in examples/*.js; do echo \"$f\"; node \"$f\" || exit 1; echo; done; echo 'Passed'"
    },
    "preferGlobal": true,
    "bin": {
        "hue": "./hue-cli.js"
    },
    "dependencies": {
        "posix-getopt": "~1.0.0",
        "hue.js": "https://github.com/bahamas10/hue.js/tarball/master",
        "latest": "~0.1.1",
        "css-color-names": "0.0.0",
        "extsprintf": "~1.0.2"
    },
    "devDependencies": {},
    "optionalDependencies": {},
    "engines": {
        "node": "*"
    },
    "keywords": [
        "hue",
        "philips",
        "automation"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
