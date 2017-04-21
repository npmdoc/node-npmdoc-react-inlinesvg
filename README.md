# npmdoc-react-inlinesvg

#### api documentation for  react-inlinesvg (v0.5.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-inlinesvg.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-inlinesvg) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-inlinesvg.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-inlinesvg)

#### An SVG loader for React

[![NPM](https://nodei.co/npm/react-inlinesvg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-inlinesvg)

- [https://npmdoc.github.io/node-npmdoc-react-inlinesvg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-inlinesvg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-inlinesvg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-inlinesvg/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-inlinesvg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-inlinesvg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-inlinesvg",
    "version": "0.5.5",
    "description": "An SVG loader for React",
    "repository": {
        "type": "git",
        "url": "git://github.com/matthewwithanm/react-inlinesvg.git"
    },
    "keywords": [
        "react-component",
        "react",
        "svg",
        "component"
    ],
    "author": "Matthew Dapena-Tretter <m@tthewwithanm.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/matthewwithanm/react-inlinesvg/issues"
    },
    "main": "./lib/index.js",
    "dependencies": {
        "httpplease": "^0.16",
        "once": "^1.4",
        "fbjs": "^0.8"
    },
    "devDependencies": {
        "babel-core": "^6.17",
        "babel-eslint": "^7.0",
        "babel-plugin-add-module-exports": "^0.2",
        "babel-plugin-rewire": "1.0.0",
        "babel-preset-es2015": "^6.16",
        "babel-preset-react": "^6.16",
        "babel-preset-stage-1": "^6.16",
        "babel-register": "^6.16",
        "babelify": "^7.3",
        "browserify": "^13.1",
        "browserify-shim": "^3.8",
        "cors": "^2.8",
        "enzyme": "^2.4",
        "eslint": "^3.7",
        "eslint-config-airbnb": "^12.0",
        "eslint-plugin-import": "^2.0",
        "eslint-plugin-jsx-a11y": "^2.2",
        "eslint-plugin-react": "^6.3",
        "expect": "^1.20",
        "gulp": "^3.9",
        "gulp-babel": "^6.1",
        "gulp-bump": "^2.4",
        "gulp-connect": "^5.0",
        "gulp-load-plugins": "^1.3",
        "gulp-rename": "^1.2",
        "gulp-util": "^3.0",
        "jsdom": "^9.6",
        "mocha": "^3.1",
        "react": "^15.3",
        "react-addons-test-utils": "^15.3",
        "react-dom": "^15.3",
        "vinyl-source-stream": "^1.1"
    },
    "peerDependencies": {
        "react": "^0.14 || ^15.0"
    },
    "scripts": {
        "build": "gulp build",
        "test": "gulp test-server & mocha --compilers js:babel-register; kill %1",
        "lint": "eslint -c ./.eslintrc $(find src -name '*.js')",
        "prepublish": "npm run build"
    },
    "browserify": {
        "transform": [
            [
                "babelify",
                {
                    "ignore": "/bower_components/",
                    "sourceMapRelative": "."
                }
            ]
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
