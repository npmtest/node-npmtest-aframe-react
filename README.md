# npmtest-aframe-react

#### basic test coverage for  [aframe-react (v4.1.1)](https://github.com/aframevr/aframe-react#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-aframe-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-aframe-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-aframe-react.svg)](https://travis-ci.org/npmtest/node-npmtest-aframe-react)

#### Build virtual reality experiences with A-Frame and React.

[![NPM](https://nodei.co/npm/aframe-react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aframe-react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-aframe-react/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-aframe-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-aframe-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-aframe-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-aframe-react/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-aframe-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-aframe-react/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-aframe-react/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-aframe-react/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-aframe-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-aframe-react/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-aframe-react/build/test-report.html](https://npmtest.github.io/node-npmtest-aframe-react/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-aframe-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-aframe-react/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-aframe-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aframe-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aframe-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aframe-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-aframe-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-aframe-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Ngo"
    },
    "bugs": {
        "url": "https://github.com/aframevr/aframe-react/issues"
    },
    "dependencies": {},
    "description": "Build virtual reality experiences with A-Frame and React.",
    "devDependencies": {
        "aframe": "^0.5.0",
        "babel": "^6.3.13",
        "babel-cli": "^6.3.15",
        "babel-jest": "^16.0.0",
        "babel-loader": "^6.4.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "babel-register": "^6.16.3",
        "chai": "^3.5.0",
        "chai-shallow-deep-equal": "^1.4.6",
        "jest": "^16.0.1",
        "karma": "^0.13.15",
        "karma-chai-shallow-deep-equal": "0.0.4",
        "karma-chrome-launcher": "2.0.0",
        "karma-firefox-launcher": "^0.1.7",
        "karma-mocha": "^0.2.1",
        "karma-mocha-reporter": "^1.1.3",
        "karma-sinon-chai": "^1.1.0",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.3",
        "mocha": "^3.1.2",
        "mozilla-download": "^1.1.1",
        "react": "^15.5.4",
        "react-dom": "^15.5.4",
        "react-test-renderer": "^15.5.4",
        "sinon": "1.17.5",
        "sinon-chai": "2.8.0",
        "webpack": "^2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "122af9206d9566c08db0379e4bb29193670b01ac",
        "tarball": "https://registry.npmjs.org/aframe-react/-/aframe-react-4.1.1.tgz"
    },
    "gitHead": "2257f381cedc4bf00f3b44ed0f3ae86b9832f7fe",
    "homepage": "https://github.com/aframevr/aframe-react#readme",
    "jest": {
        "testPathDirs": [
            "tests/react"
        ]
    },
    "keywords": [
        "aframe",
        "react",
        "vr",
        "a-frame",
        "aframevr",
        "mozvr",
        "reactvr",
        "react-vr",
        "react-component",
        "virtual-reality",
        "webvr"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "ngokevin"
        }
    ],
    "name": "aframe-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "*",
        "react-dom": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aframevr/aframe-react.git"
    },
    "scripts": {
        "build": "babel src -d dist",
        "prepublish": "npm run build",
        "test": "karma start ./tests/browser/karma.conf.js",
        "test:chrome": "karma start ./tests/browser/karma.conf.js --browsers Chrome",
        "test:firefox": "karma start ./tests/browser/karma.conf.js --browsers Firefox",
        "test:react": "jest --watch"
    },
    "version": "4.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
