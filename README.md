# npmtest-insight

#### test coverage for  [insight (v0.8.4)](https://github.com/yeoman/insight#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-insight.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-insight) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-insight.svg)](https://travis-ci.org/npmtest/node-npmtest-insight)

#### Understand how your tool is being used by anonymously reporting usage metrics to Google Analytics or Yandex.Metrica

[![NPM](https://nodei.co/npm/insight.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/insight)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-insight/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-insight/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-insight/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-insight/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-insight/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-insight/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-insight/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-insight/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-insight/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-insight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-insight/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-insight/build/test-report.html](https://npmtest.github.io/node-npmtest-insight/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-insight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-insight/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-insight/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-insight/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-insight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-insight/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-insight/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-insight/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/yeoman/insight/issues"
    },
    "dependencies": {
        "async": "^1.4.2",
        "chalk": "^1.0.0",
        "configstore": "^1.0.0",
        "inquirer": "^0.10.0",
        "lodash.debounce": "^3.0.1",
        "object-assign": "^4.0.1",
        "os-name": "^1.0.0",
        "request": "^2.74.0",
        "tough-cookie": "^2.0.0",
        "uuid": "^3.0.0"
    },
    "description": "Understand how your tool is being used by anonymously reporting usage metrics to Google Analytics or Yandex.Metrica",
    "devDependencies": {
        "mocha": "*",
        "object-values": "^1.0.0",
        "sinon": "*",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "671caf65b47c9fe8c3d1b3206cf45bb211b75884",
        "tarball": "https://registry.npmjs.org/insight/-/insight-0.8.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "3edcaf4ead5e94967b721e39a082e3dc6821faf8",
    "homepage": "https://github.com/yeoman/insight#readme",
    "keywords": [
        "package",
        "stats",
        "google",
        "analytics",
        "track",
        "metrics",
        "stats",
        "yandex",
        "metrica"
    ],
    "license": "BSD-2-Clause",
    "main": "lib",
    "maintainers": [
        {
            "name": "sindresorhus"
        },
        {
            "name": "passy"
        },
        {
            "name": "sboudrias"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "rayshan"
        },
        {
            "name": "arthurvr"
        }
    ],
    "name": "insight",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/insight.git"
    },
    "scripts": {
        "test": "xo && mocha --timeout 20000 --reporter spec test/test.js"
    },
    "version": "0.8.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
