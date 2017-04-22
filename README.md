# npmtest-react-google-places-suggest

#### basic test coverage for  [react-google-places-suggest (v2.1.1)](https://github.com/xuopled/react-google-places-suggest#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-google-places-suggest.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-google-places-suggest) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-google-places-suggest.svg)](https://travis-ci.org/npmtest/node-npmtest-react-google-places-suggest)

#### React component to select geolocated suggestion from Google Maps Places API

[![NPM](https://nodei.co/npm/react-google-places-suggest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-google-places-suggest)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-google-places-suggest/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-google-places-suggest/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-google-places-suggest/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/test-report.html](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-google-places-suggest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-google-places-suggest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-google-places-suggest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-google-places-suggest/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-google-places-suggest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cédric Delpoux"
    },
    "bugs": {
        "url": "https://github.com/xuopled/react-google-places-suggest/issues"
    },
    "dependencies": {
        "classnames": "^2.1.3"
    },
    "description": "React component to select geolocated suggestion from Google Maps Places API",
    "devDependencies": {
        "autoprefixer": "~6.5.3",
        "babel-cli": "~6.18.0",
        "babel-core": "~6.18.2",
        "babel-eslint": "~7.1.1",
        "babel-loader": "^6.2.8",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "~6.16.0",
        "babel-preset-stage-1": "6.16.0",
        "eslint": "~3.11.1",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "~6.8.0",
        "postcss-cli": "~2.6.0",
        "webpack": "^1.13.3"
    },
    "directories": {},
    "dist": {
        "shasum": "cb959fb808c05b6db39c43d3824015900e5ffb05",
        "tarball": "https://registry.npmjs.org/react-google-places-suggest/-/react-google-places-suggest-2.1.1.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "a829839bcb24d2e4a87f0c96c21f74f15b24de12",
    "homepage": "https://github.com/xuopled/react-google-places-suggest#readme",
    "keywords": [
        "react",
        "google",
        "maps",
        "places",
        "googlemaps",
        "geosuggest"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "xuopled"
        }
    ],
    "name": "react-google-places-suggest",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "~15.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/xuopled/react-google-places-suggest.git"
    },
    "scripts": {
        "build": "babel ./src --out-dir ./lib --source-maps && postcss --use autoprefixer src/index.css -d ./lib",
        "clean": "rm -rf lib",
        "lint": "eslint src/",
        "prepublish": "npm run clean && npm run build"
    },
    "style": "lib/index.css",
    "version": "2.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
