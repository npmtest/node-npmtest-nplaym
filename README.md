# npmtest-nplaym

#### basic test coverage for  nplaym (v1.3.8)  [![npm package](https://img.shields.io/npm/v/npmtest-nplaym.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nplaym) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nplaym.svg)](https://travis-ci.org/npmtest/node-npmtest-nplaym)

#### A wrapper for npm so you can play a Space-Invaders-a-like game while installing.

[![NPM](https://nodei.co/npm/nplaym.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nplaym)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nplaym/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nplaym/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nplaym/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nplaym/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nplaym/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nplaym/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nplaym/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nplaym/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nplaym/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nplaym/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nplaym/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nplaym/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nplaym/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nplaym/build/test-report.html](https://npmtest.github.io/node-npmtest-nplaym/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nplaym/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nplaym/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nplaym/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nplaym/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nplaym/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nplaym/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nplaym/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nplaym/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nplaym",
    "version": "1.3.8",
    "description": "A wrapper for npm so you can play a Space-Invaders-a-like game while installing.",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "dev": "babel --source-maps --out-dir lib/ src/ --watch",
        "build": "rollup -i src/index.js -o bin/nplaym --banner '#!/usr/bin/env node' --config rollup.config.js"
    },
    "bin": {
        "nplaym": "./bin/nplaym"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/JonathanUsername/nplaym.git"
    },
    "author": "Jonathan King",
    "license": "ISC",
    "dependencies": {
        "child_pty": "~3.0.1",
        "colors": "~1.1.2",
        "extend": "~3.0.0",
        "keypress": "~0.2.1",
        "lodash": "~4.6.1",
        "nan": "~2.2.0",
        "node-terminal": "~0.1.1"
    },
    "devDependencies": {
        "babel-cli": "~6.6.5",
        "babel-preset-es2015": "~6.6.0",
        "babel-preset-es2015-rollup": "~1.1.1",
        "babelify": "~7.2.0",
        "rollup-plugin-babel": "~2.4.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
