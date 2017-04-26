# npmtest-ember-cli-mirage

#### basic test coverage for  [ember-cli-mirage (v0.3.1)](https://github.com/samselikoff/ember-cli-mirage)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-mirage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-mirage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-mirage.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-mirage)

#### A client-side HTTP server to develop, test and demo your Ember app

[![NPM](https://nodei.co/npm/ember-cli-mirage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-mirage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-mirage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-cli-mirage/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-mirage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-mirage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-mirage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-mirage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-mirage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-mirage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-mirage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sam Selikoff"
    },
    "bugs": {
        "url": "https://github.com/samselikoff/ember-cli-mirage/issues"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.2",
        "broccoli-merge-trees": "^1.1.0",
        "broccoli-unwatched-tree": "^0.1.1",
        "chalk": "^1.1.1",
        "ember-cli-babel": "^5.1.7",
        "ember-cli-node-assets": "^0.1.4",
        "ember-inflector": "^1.9.2",
        "ember-lodash": "^4.0",
        "exists-sync": "0.0.3",
        "fake-xml-http-request": "^1.4.0",
        "faker": "^3.0.0",
        "pretender": "^1.4.2",
        "route-recognizer": "^0.2.3"
    },
    "description": "A client-side HTTP server to develop, test and demo your Ember app",
    "devDependencies": {
        "active-model-adapter": "^2.0.3",
        "broccoli-asset-rev": "^2.4.5",
        "chai": "2.0.0",
        "ember-ajax": "^2.4.1",
        "ember-cli": "^2.9.1",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-content-security-policy": "0.4.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "3.0.0",
        "ember-cli-htmlbars": "^1.0.10",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-qunit": "^3.0.1",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.10.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-disable-proxy-controllers": "^1.0.1",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "ember-sinon": "0.5.1",
        "eslint-plugin-ember-suave": "^1.0.0",
        "loader.js": "^4.0.10",
        "mocha": "^2.1.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "2541d624f4994fae3188fcd76a768e8eaff71c4b",
        "tarball": "https://registry.npmjs.org/ember-cli-mirage/-/ember-cli-mirage-0.3.1.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "8760bffee42a51f793d745b4b0fd819cf3dbb30e",
    "homepage": "https://github.com/samselikoff/ember-cli-mirage",
    "keywords": [
        "ember-addon",
        "pretender",
        "testing",
        "prototype",
        "server"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "cibernox"
        },
        {
            "name": "rwjblue"
        },
        {
            "name": "samselikoff"
        }
    ],
    "name": "ember-cli-mirage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/samselikoff/ember-cli-mirage.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each && mocha tests/**/*-test-node.js"
    },
    "version": "0.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
