# npmtest-react-virtualized

#### basic test coverage for  [react-virtualized (v9.7.3)](https://github.com/bvaughn/react-virtualized)  [![npm package](https://img.shields.io/npm/v/npmtest-react-virtualized.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-virtualized) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-virtualized.svg)](https://travis-ci.org/npmtest/node-npmtest-react-virtualized)

#### React components for efficiently rendering large, scrollable lists and tabular data

[![NPM](https://nodei.co/npm/react-virtualized.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-virtualized)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-virtualized/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-virtualized/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-virtualized/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-virtualized/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-virtualized/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-virtualized/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-virtualized/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-virtualized/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-virtualized/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-virtualized/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-virtualized/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-virtualized/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-virtualized/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-virtualized/build/test-report.html](https://npmtest.github.io/node-npmtest-react-virtualized/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-virtualized/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-virtualized/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-virtualized/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-virtualized/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-virtualized/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian Vaughn"
    },
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/bvaughn/react-virtualized/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "classnames": "^2.2.3",
        "dom-helpers": "^2.4.0 || ^3.0.0",
        "loose-envify": "^1.3.0",
        "prop-types": "^15.5.4"
    },
    "description": "React components for efficiently rendering large, scrollable lists and tabular data",
    "devDependencies": {
        "autoprefixer": "^6.2.3",
        "babel-cli": "6.8.0",
        "babel-core": "^6.5.1",
        "babel-eslint": "^6.0.4",
        "babel-jest": "^18.0.0",
        "babel-loader": "^6.2.3",
        "babel-plugin-__coverage__": "^0.111111.11",
        "babel-plugin-react-transform": "^2.0.0",
        "babel-plugin-transform-react-inline-elements": "^6.6.5",
        "babel-plugin-transform-react-remove-prop-types": "^0.2.10",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-plugin-typecheck": "^3.9.0",
        "babel-polyfill": "^6.5.0",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-es2015-rollup": "3.0.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "bluebird": "^3.0.5",
        "codecov": "^1.0.1",
        "codemirror": "^5.18.0",
        "cross-env": "^1.0.7",
        "css-loader": "^0.23.0",
        "express": "^4.13.3",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.8.5",
        "flow-bin": "^0.39.0",
        "fs-extra": "^0.30.0",
        "gh-pages": "^0.11.0",
        "html-webpack-plugin": "^2.16.1",
        "immutable": "^3.7.5",
        "jest": "^18.1.0",
        "postcss": "^5.0.14",
        "postcss-cli": "^2.3.3",
        "postcss-loader": "^0.9.1",
        "raf": "^3.3.0",
        "react": "16.0.0-alpha.2",
        "react-addons-test-utils": "16.0.0-alpha.2",
        "react-codemirror": "^0.2.6",
        "react-dom": "16.0.0-alpha.2",
        "react-router": "4.0",
        "react-router-dom": "4.0",
        "react-transform-catch-errors": "^1.0.2",
        "react-transform-hmr": "^1.0.2",
        "redbox-react": "^1.0.1",
        "rimraf": "^2.4.3",
        "standard": "^7.0.1",
        "style-loader": "^0.13.0",
        "watch": "^0.18.0",
        "webpack": "^1.9.6",
        "webpack-dashboard": "0.0.1",
        "webpack-dev-server": "^1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5be2bbc0316151ee1c00d133f7a5f9727874f756",
        "tarball": "https://registry.npmjs.org/react-virtualized/-/react-virtualized-9.7.3.tgz"
    },
    "files": [
        "dist",
        "styles.css"
    ],
    "gitHead": "2462beacc7c1c405004f18dbde2e8ed3db597d05",
    "homepage": "https://github.com/bvaughn/react-virtualized",
    "jest": {
        "setupFiles": [
            "./source/jest-setup.js"
        ],
        "testPathDirs": [
            "./source"
        ],
        "testRegex": ".jest.js",
        "verbose": true
    },
    "jsnext:main": "dist/es/index.js",
    "keywords": [
        "react",
        "reactjs",
        "react-component",
        "virtual",
        "list",
        "scrolling",
        "infinite",
        "virtualized",
        "table",
        "fixed",
        "header",
        "flex",
        "flexbox",
        "grid",
        "spreadsheet"
    ],
    "license": "MIT",
    "main": "dist/commonjs/index.js",
    "maintainers": [
        {
            "name": "brianvaughn"
        }
    ],
    "module": "dist/es/index.js",
    "name": "react-virtualized",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.3.0 || ^16.0.0-alpha",
        "react-dom": "^15.3.0 || ^16.0.0-alpha"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bvaughn/react-virtualized.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:css && npm run build:es && npm run build:demo && npm run build:umd",
        "build:commonjs": "npm run clean:commonjs && cross-env NODE_ENV=production cross-env BABEL_ENV=commonjs babel source --out-dir dist/commonjs --ignore *.example.js,*.test.js,source/demo/,source/tests.js",
        "build:css": "postcss --config postcss.config.js --use autoprefixer source/styles.css > styles.css",
        "build:demo": "npm run clean:demo && cross-env NODE_ENV=production webpack --config webpack.config.demo.js -p --bail",
        "build:es": "npm run clean:es && cross-env NODE_ENV=production cross-env BABEL_ENV=es babel source --out-dir dist/es --ignore *.example.js,*.test.js,source/demo/,source/tests.js",
        "build:umd": "npm run clean:umd && cross-env NODE_ENV=production webpack --config webpack.config.umd.js --bail",
        "clean": "npm run clean:commonjs && npm run clean:demo && npm run clean:es && npm run clean:umd",
        "clean:commonjs": "rimraf dist/commonjs",
        "clean:demo": "rimraf build",
        "clean:es": "rimraf dist/es",
        "clean:umd": "rimraf dist/umd",
        "deploy": "gh-pages -d build",
        "lint": "standard",
        "postpublish": "npm run deploy",
        "posttest": "[ -z \"$CI\" ] || codecov",
        "prebuild": "npm run lint",
        "predeploy": "cp ./circle.yml ./build/",
        "prepublish": "npm run build",
        "start": "cross-env NODE_ENV=development webpack-dev-server --hot --inline --config webpack.config.dev.js",
        "test": "npm run lint && npm run test:jest",
        "test:jest": "jest --no-watchman --runInBand",
        "watch": "watch 'clear && npm run test -s' source",
        "watch:jest": "jest --no-watchman --watch"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "dist",
            "playground",
            "source/vendor"
        ],
        "global": [
            "afterAll",
            "afterEach",
            "beforeAll",
            "beforeEach",
            "describe",
            "expect",
            "fdescribe",
            "fit",
            "getComputedStyle",
            "it",
            "jest",
            "spyOn"
        ]
    },
    "user": "bvaughn",
    "version": "9.7.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
