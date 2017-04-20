# npmtest-ungit

#### basic test coverage for  [ungit (v1.1.14)](https://github.com/FredrikNoren/ungit#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ungit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ungit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ungit.svg)](https://travis-ci.org/npmtest/node-npmtest-ungit)

#### Git made easy

[![NPM](https://nodei.co/npm/ungit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ungit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ungit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ungit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ungit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ungit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ungit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ungit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ungit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ungit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ungit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ungit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ungit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ungit/build/test-report.html](https://npmtest.github.io/node-npmtest-ungit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ungit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ungit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ungit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ungit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ungit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ungit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ungit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ungit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fredrik Norén"
    },
    "bin": {
        "ungit": "./bin/ungit",
        "0ungit-credentials-helper": "./bin/credentials-helper"
    },
    "bugs": {
        "url": "https://github.com/FredrikNoren/ungit/issues"
    },
    "dependencies": {
        "async": "~2.1.4",
        "bluebird": "~3.4.7",
        "blueimp-md5": "~2.6.0",
        "body-parser": "~1.15.2",
        "color": "~1.0.3",
        "cookie-parser": "~1.4.3",
        "crossroads": "~0.12.2",
        "diff2html": "^2.3.0",
        "express": "~4.15.2",
        "express-session": "~1.15.2",
        "forever-monitor": "~1.1.0",
        "getmac": "~1.2.1",
        "hasher": "~1.2.0",
        "ignore": "~3.2.6",
        "keen.io": "~0.1.3",
        "knockout": "~3.4.2",
        "lodash": "~4.17.4",
        "mkdirp": "~0.5.1",
        "moment": "~2.18.1",
        "node-cache": "~4.1.1",
        "npm": "~4.5.0",
        "npm-registry-client": "~8.1.0",
        "octicons": "~3.5.0",
        "open": "~0.0.5",
        "os-homedir": "~1.0.2",
        "passport": "~0.3.2",
        "passport-local": "~1.0.0",
        "raven": "~1.2.0",
        "rc": "^1.1.7",
        "rimraf": "~2.6.1",
        "semver": "~5.3.0",
        "serve-static": "~1.12.1",
        "signals": "~1.0.0",
        "snapsvg": "~0.5.1",
        "socket.io": "~1.7.3",
        "superagent": "^0.21.0",
        "temp": "~0.8.3",
        "winston": "~2.3.1",
        "yargs": "^7.0.2"
    },
    "description": "Git made easy",
    "devDependencies": {
        "ansi-color": "~0.2.1",
        "babel-preset-es2015": "~6.24.0",
        "babel-preset-stage-0": "~6.22.0",
        "browserify": "~14.1.0",
        "electron-packager": "~8.6.0",
        "expect.js": "~0.3.1",
        "grunt": "~1.0.1",
        "grunt-babel": "~6.0.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-imagemin": "~1.0.1",
        "grunt-contrib-jshint": "~1.1.0",
        "grunt-contrib-less": "~1.4.1",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-image-embed": "0.3.3",
        "grunt-lineending": "~1.0.0",
        "grunt-mocha-istanbul": "~5.0.2",
        "grunt-mocha-test": "~0.13.2",
        "grunt-plato": "~1.4.0",
        "grunt-release": "~0.14.0",
        "istanbul": "~0.4.5",
        "mocha": "~3.2.0",
        "phantomjs-prebuilt": "~2.1.14",
        "supertest": "~0.15.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e65f05f541bc8b829f9720f28e74c4a12c7b6dd2",
        "tarball": "https://registry.npmjs.org/ungit/-/ungit-1.1.14.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "cf45b289cd81891f5af33a370bc20c5baf20a60e",
    "homepage": "https://github.com/FredrikNoren/ungit#readme",
    "license": "MIT",
    "main": "public/main.js",
    "maintainers": [
        {
            "name": "fredriknoren"
        }
    ],
    "name": "ungit",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/FredrikNoren/ungit.git"
    },
    "scripts": {
        "start": "node ./bin/ungit",
        "test": "grunt test"
    },
    "ungitPluginApiVersion": "0.2.0",
    "version": "1.1.14",
    "window": {
        "title": "Ungit",
        "icon": "icon.png",
        "toolbar": false,
        "frame": false,
        "show": false,
        "width": 1000,
        "height": 600,
        "position": "center",
        "min_width": 400,
        "min_height": 200
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
