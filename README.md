# npmdoc-cost-of-modules

#### api documentation for  [cost-of-modules (v1.0.1)](https://github.com/siddharthkp/cost-of-modules#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-cost-of-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cost-of-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cost-of-modules.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cost-of-modules)

#### Find out which of your dependencies are slowing you down 🐢

[![NPM](https://nodei.co/npm/cost-of-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cost-of-modules)

- [https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cost-of-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "siddharthkp"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "bin": {
        "cost-of-modules": "lib/index.js"
    },
    "bugs": {
        "url": "https://github.com/siddharthkp/cost-of-modules/issues"
    },
    "dependencies": {
        "ansi-regex": "2.0.0",
        "cli-table2": "0.2.0",
        "colors": "1.1.2",
        "fs-extra": "2.1.0",
        "sync-exec": "0.6.2",
        "yargs-parser": "4.0.2"
    },
    "description": "Find out which of your dependencies are slowing you down 🐢",
    "devDependencies": {
        "ava": "0.16.0",
        "babel-cli": "6.18.0",
        "babel-preset-es2015": "6.18.0",
        "eslint": "3.8.1",
        "eslint-config-airbnb": "12.0.0",
        "eslint-plugin-import": "1.16.0",
        "eslint-plugin-jsx-a11y": "2.2.3",
        "eslint-plugin-react": "6.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f926126b553ccf0de3a998ab79ae738241525ed3",
        "tarball": "https://registry.npmjs.org/cost-of-modules/-/cost-of-modules-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 5.0.0",
        "npm": ">= 3.0.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "1d49fa49a500603b81e185e9aa28ca4e7f972fcc",
    "homepage": "https://github.com/siddharthkp/cost-of-modules#readme",
    "keywords": [
        "cost",
        "modules",
        "bloat"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "siddharthkp"
        }
    ],
    "name": "cost-of-modules",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/siddharthkp/cost-of-modules.git"
    },
    "scripts": {
        "ava": "ava test/lib/*.js -s --no-cache",
        "build": "babel src -d lib && babel test/src -d test/lib",
        "lint": "eslint src",
        "test": "npm run lint && npm run build && npm run ava"
    },
    "version": "1.0.1",
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
