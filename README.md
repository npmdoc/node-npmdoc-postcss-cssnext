# api documentation for  [postcss-cssnext (v2.10.0)](http://cssnext.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-postcss-cssnext.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-postcss-cssnext) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-postcss-cssnext.svg)](https://travis-ci.org/npmdoc/node-npmdoc-postcss-cssnext)
#### Use tomorrow’s CSS syntax, today

[![NPM](https://nodei.co/npm/postcss-cssnext.png?downloads=true)](https://www.npmjs.com/package/postcss-cssnext)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-postcss-cssnext%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-postcss-cssnext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maxime Thirouin"
    },
    "babel": {
        "presets": [
            "babel-preset-react",
            "babel-preset-es2015",
            "babel-preset-stage-1"
        ]
    },
    "bugs": {
        "url": "https://github.com/MoOx/postcss-cssnext/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.0.2",
        "caniuse-api": "^1.5.3",
        "chalk": "^1.1.1",
        "pixrem": "^3.0.0",
        "pleeease-filters": "^3.0.0",
        "postcss": "^5.0.4",
        "postcss-apply": "^0.3.0",
        "postcss-attribute-case-insensitive": "^1.0.1",
        "postcss-calc": "^5.0.0",
        "postcss-color-function": "^2.0.0",
        "postcss-color-gray": "^3.0.0",
        "postcss-color-hex-alpha": "^2.0.0",
        "postcss-color-hsl": "^1.0.5",
        "postcss-color-hwb": "^2.0.0",
        "postcss-color-rebeccapurple": "^2.0.0",
        "postcss-color-rgb": "^1.1.4",
        "postcss-color-rgba-fallback": "^2.0.0",
        "postcss-custom-media": "^5.0.0",
        "postcss-custom-properties": "^5.0.0",
        "postcss-custom-selectors": "^3.0.0",
        "postcss-font-family-system-ui": "^1.0.1",
        "postcss-font-variant": "^2.0.0",
        "postcss-initial": "^1.3.1",
        "postcss-media-minmax": "^2.1.0",
        "postcss-nesting": "^2.0.5",
        "postcss-pseudo-class-any-link": "^1.0.0",
        "postcss-pseudoelements": "^3.0.0",
        "postcss-replace-overflow-wrap": "^1.0.0",
        "postcss-selector-matches": "^2.0.0",
        "postcss-selector-not": "^2.0.0"
    },
    "description": "Use tomorrow’s CSS syntax, today",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.2",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "babel-tape-runner": "^2.0.1",
        "classnames": "^2.1.1",
        "css-loader": "^0.13.1",
        "cssrecipes-custom-media-queries": "^0.3.0",
        "cssrecipes-defaults": "^0.5.0",
        "cssrecipes-grid": "^0.4.0",
        "cssrecipes-utils": "^0.5.0",
        "cssrecipes-vertical-rhythm": "^0.6.0",
        "eslint": "^2.4.0",
        "eslint-config-i-am-meticulous": "^3.0.0",
        "eslint-loader": "^1.0.0",
        "eslint-plugin-react": "^3.0.0",
        "extract-text-webpack-plugin": "^0.8.0",
        "file-loader": "^0.8.3",
        "highlight.js": "^8.6.0",
        "isogram": "^0.5.0",
        "js-yaml": "^3.3.1",
        "json-loader": "^0.5.2",
        "markdown-it": "^4.2.1",
        "markdown-it-toc-and-anchor": "^1.0.1",
        "metalsmith": "^2.0.1",
        "metalsmith-collections": "^0.7.0",
        "metalsmith-filenames": "^1.0.0",
        "metalsmith-md": "^2.0.1",
        "metalsmith-react": "^2.0.1",
        "metalsmith-rename": "^1.0.0",
        "metalsmith-rss": "^1.0.0",
        "metalsmith-url": "^1.0.0",
        "metalsmith-watch": "^1.0.1",
        "nano-logger": "^1.0.0",
        "node-libs-browser": "^0.5.0",
        "normalize.css": "^3.0.3",
        "npmpub": "^3.1.0",
        "object-assign": "^3.0.0",
        "opn": "^1.0.2",
        "postcss-browser-reporter": "^0.4.0",
        "postcss-import": "^7.1.3",
        "postcss-loader": "^0.8.0",
        "postcss-reporter": "^1.3.0",
        "postcss-url": "^5.0.2",
        "react": "^15.0.0-rc.1",
        "react-dom": "^15.0.0-rc.1",
        "react-svg-inline": "^1.0.1",
        "rimraf": "^2.4.3",
        "style-loader": "^0.12.2",
        "tape": "^4.2.0",
        "to-slug-case": "^0.1.2",
        "webpack": "^1.9.7",
        "webpack-dev-server": "^1.8.2",
        "webpack-nano-logs": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "30e0dddcfb978eae2523a340aa2c8ba49c5d7103",
        "tarball": "https://registry.npmjs.org/postcss-cssnext/-/postcss-cssnext-2.10.0.tgz"
    },
    "eslintConfig": {
        "extends": "eslint-config-i-am-meticulous/react"
    },
    "files": [
        "docs/content",
        "lib",
        "src",
        "!**/__tests__"
    ],
    "gitHead": "6577f6c196325e5e10d4b4ce704d5987b268433a",
    "homepage": "http://cssnext.io/",
    "keywords": [
        "postcss",
        "postcss-plugin",
        "css",
        "w3c",
        "cssnext"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "moox",
            "email": "m@moox.io"
        }
    ],
    "name": "postcss-cssnext",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MoOx/postcss-cssnext.git"
    },
    "scripts": {
        "#lint": "even if there is a .eslintignore symlink, we use an explicit command because windows don't like unix symlink",
        "#tape": "to avoid really slow tests, we run babel once & run tests on the result",
        "_docs-deploy": "GIT_DEPLOY_DIR=docs/dist ./docs/scripts/deploy-to-gh-pages.sh -v",
        "babelify": "babel src --out-dir lib",
        "docs-build": "babel-node docs/scripts/build",
        "docs-deploy": "npm run docs-test && npm run _docs-deploy",
        "docs-start": "npm run docs-build -- --dev --dev-server --open",
        "docs-test": "npm run docs-build -- --production",
        "lint": "eslint --ignore-path .gitignore .",
        "postrelease": "npm run docs-deploy",
        "prebabelify": "rimraf lib",
        "predocs-start": "npm run prepublish",
        "prepublish": "npm run babelify",
        "release": "npmpub",
        "tape": "tape \"lib/__tests__/*.js\"",
        "test": "npm run lint && npm run babelify && npm run tape"
    },
    "version": "2.10.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module postcss-cssnext](#apidoc.module.postcss-cssnext)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.</span>process (root, opts)](#apidoc.element.postcss-cssnext.process)
1.  object <span class="apidocSignatureSpan">postcss-cssnext.</span>features
1.  object <span class="apidocSignatureSpan">postcss-cssnext.</span>warn_for_duplicates

#### [module postcss-cssnext.features](#apidoc.module.postcss-cssnext.features)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>applyRule (options)](#apidoc.element.postcss-cssnext.features.applyRule)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>attributeCaseInsensitive (options)](#apidoc.element.postcss-cssnext.features.attributeCaseInsensitive)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>autoprefixer (options)](#apidoc.element.postcss-cssnext.features.autoprefixer)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>calc (options)](#apidoc.element.postcss-cssnext.features.calc)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorFunction (options)](#apidoc.element.postcss-cssnext.features.colorFunction)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorGray (options)](#apidoc.element.postcss-cssnext.features.colorGray)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorHexAlpha (options)](#apidoc.element.postcss-cssnext.features.colorHexAlpha)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorHsl (options)](#apidoc.element.postcss-cssnext.features.colorHsl)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorHwb (options)](#apidoc.element.postcss-cssnext.features.colorHwb)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorRebeccapurple (options)](#apidoc.element.postcss-cssnext.features.colorRebeccapurple)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorRgb (options)](#apidoc.element.postcss-cssnext.features.colorRgb)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorRgba (options)](#apidoc.element.postcss-cssnext.features.colorRgba)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>customMedia (options)](#apidoc.element.postcss-cssnext.features.customMedia)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>customProperties (options)](#apidoc.element.postcss-cssnext.features.customProperties)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>customSelectors (options)](#apidoc.element.postcss-cssnext.features.customSelectors)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>filter (options)](#apidoc.element.postcss-cssnext.features.filter)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>fontFamilySystemUi (options)](#apidoc.element.postcss-cssnext.features.fontFamilySystemUi)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>fontVariant (options)](#apidoc.element.postcss-cssnext.features.fontVariant)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>initial (options)](#apidoc.element.postcss-cssnext.features.initial)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>mediaQueriesRange (options)](#apidoc.element.postcss-cssnext.features.mediaQueriesRange)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>nesting (options)](#apidoc.element.postcss-cssnext.features.nesting)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>overflowWrap (options)](#apidoc.element.postcss-cssnext.features.overflowWrap)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoClassAnyLink (options)](#apidoc.element.postcss-cssnext.features.pseudoClassAnyLink)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoClassMatches (options)](#apidoc.element.postcss-cssnext.features.pseudoClassMatches)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoClassNot (options)](#apidoc.element.postcss-cssnext.features.pseudoClassNot)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoElements (options)](#apidoc.element.postcss-cssnext.features.pseudoElements)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>rem (options)](#apidoc.element.postcss-cssnext.features.rem)

#### [module postcss-cssnext.warn_for_duplicates](#apidoc.module.postcss-cssnext.warn_for_duplicates)
1.  [function <span class="apidocSignatureSpan">postcss-cssnext.warn_for_duplicates.</span>default ()](#apidoc.element.postcss-cssnext.warn_for_duplicates.default)
1.  object <span class="apidocSignatureSpan">postcss-cssnext.warn_for_duplicates.</span>spotted



# <a name="apidoc.module.postcss-cssnext"></a>[module postcss-cssnext](#apidoc.module.postcss-cssnext)

#### <a name="apidoc.element.postcss-cssnext.process"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.</span>process (root, opts)](#apidoc.element.postcss-cssnext.process)
- description and source-code
```javascript
process = function (root, opts) {
  return postcss([creator(opts)]).process(root, opts);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.postcss-cssnext.features"></a>[module postcss-cssnext.features](#apidoc.module.postcss-cssnext.features)

#### <a name="apidoc.element.postcss-cssnext.features.applyRule"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>applyRule (options)](#apidoc.element.postcss-cssnext.features.applyRule)
- description and source-code
```javascript
function applyRule(options) {
  return require("postcss-apply")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.attributeCaseInsensitive"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>attributeCaseInsensitive (options)](#apidoc.element.postcss-cssnext.features.attributeCaseInsensitive)
- description and source-code
```javascript
function attributeCaseInsensitive(options) {
  return require("postcss-attribute-case-insensitive")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.autoprefixer"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>autoprefixer (options)](#apidoc.element.postcss-cssnext.features.autoprefixer)
- description and source-code
```javascript
function autoprefixer(options) {
  return require("autoprefixer")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.calc"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>calc (options)](#apidoc.element.postcss-cssnext.features.calc)
- description and source-code
```javascript
function calc(options) {
  return require("postcss-calc")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorFunction"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorFunction (options)](#apidoc.element.postcss-cssnext.features.colorFunction)
- description and source-code
```javascript
function colorFunction(options) {
  return require("postcss-color-function")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorGray"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorGray (options)](#apidoc.element.postcss-cssnext.features.colorGray)
- description and source-code
```javascript
function colorGray(options) {
  return require("postcss-color-gray")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorHexAlpha"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorHexAlpha (options)](#apidoc.element.postcss-cssnext.features.colorHexAlpha)
- description and source-code
```javascript
function colorHexAlpha(options) {
  return require("postcss-color-hex-alpha")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorHsl"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorHsl (options)](#apidoc.element.postcss-cssnext.features.colorHsl)
- description and source-code
```javascript
function colorHsl(options) {
  return require("postcss-color-hsl")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorHwb"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorHwb (options)](#apidoc.element.postcss-cssnext.features.colorHwb)
- description and source-code
```javascript
function colorHwb(options) {
  return require("postcss-color-hwb")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorRebeccapurple"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorRebeccapurple (options)](#apidoc.element.postcss-cssnext.features.colorRebeccapurple)
- description and source-code
```javascript
function colorRebeccapurple(options) {
  return require("postcss-color-rebeccapurple")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorRgb"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorRgb (options)](#apidoc.element.postcss-cssnext.features.colorRgb)
- description and source-code
```javascript
function colorRgb(options) {
  return require("postcss-color-rgb")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.colorRgba"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>colorRgba (options)](#apidoc.element.postcss-cssnext.features.colorRgba)
- description and source-code
```javascript
function colorRgba(options) {
  return require("postcss-color-rgba-fallback")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.customMedia"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>customMedia (options)](#apidoc.element.postcss-cssnext.features.customMedia)
- description and source-code
```javascript
function customMedia(options) {
  return require("postcss-custom-media")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.customProperties"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>customProperties (options)](#apidoc.element.postcss-cssnext.features.customProperties)
- description and source-code
```javascript
function customProperties(options) {
  return require("postcss-custom-properties")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.customSelectors"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>customSelectors (options)](#apidoc.element.postcss-cssnext.features.customSelectors)
- description and source-code
```javascript
function customSelectors(options) {
  return require("postcss-custom-selectors")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.filter"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>filter (options)](#apidoc.element.postcss-cssnext.features.filter)
- description and source-code
```javascript
function filter(options) {
  return require("pleeease-filters")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.fontFamilySystemUi"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>fontFamilySystemUi (options)](#apidoc.element.postcss-cssnext.features.fontFamilySystemUi)
- description and source-code
```javascript
function fontFamilySystemUi(options) {
  return require("postcss-font-family-system-ui")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.fontVariant"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>fontVariant (options)](#apidoc.element.postcss-cssnext.features.fontVariant)
- description and source-code
```javascript
function fontVariant(options) {
  return require("postcss-font-variant")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.initial"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>initial (options)](#apidoc.element.postcss-cssnext.features.initial)
- description and source-code
```javascript
function initial(options) {
  return require("postcss-initial")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.mediaQueriesRange"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>mediaQueriesRange (options)](#apidoc.element.postcss-cssnext.features.mediaQueriesRange)
- description and source-code
```javascript
function mediaQueriesRange(options) {
  return require("postcss-media-minmax")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.nesting"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>nesting (options)](#apidoc.element.postcss-cssnext.features.nesting)
- description and source-code
```javascript
function nesting(options) {
  return require("postcss-nesting")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.overflowWrap"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>overflowWrap (options)](#apidoc.element.postcss-cssnext.features.overflowWrap)
- description and source-code
```javascript
function overflowWrap(options) {
  return require("postcss-replace-overflow-wrap")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.pseudoClassAnyLink"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoClassAnyLink (options)](#apidoc.element.postcss-cssnext.features.pseudoClassAnyLink)
- description and source-code
```javascript
function pseudoClassAnyLink(options) {
  return require("postcss-pseudo-class-any-link")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.pseudoClassMatches"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoClassMatches (options)](#apidoc.element.postcss-cssnext.features.pseudoClassMatches)
- description and source-code
```javascript
function pseudoClassMatches(options) {
  return require("postcss-selector-matches")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.pseudoClassNot"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoClassNot (options)](#apidoc.element.postcss-cssnext.features.pseudoClassNot)
- description and source-code
```javascript
function pseudoClassNot(options) {
  return require("postcss-selector-not")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.pseudoElements"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>pseudoElements (options)](#apidoc.element.postcss-cssnext.features.pseudoElements)
- description and source-code
```javascript
function pseudoElements(options) {
  return require("postcss-pseudoelements")(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.postcss-cssnext.features.rem"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.features.</span>rem (options)](#apidoc.element.postcss-cssnext.features.rem)
- description and source-code
```javascript
function rem(options) {
  return require("pixrem")(options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.postcss-cssnext.warn_for_duplicates"></a>[module postcss-cssnext.warn_for_duplicates](#apidoc.module.postcss-cssnext.warn_for_duplicates)

#### <a name="apidoc.element.postcss-cssnext.warn_for_duplicates.default"></a>[function <span class="apidocSignatureSpan">postcss-cssnext.warn_for_duplicates.</span>default ()](#apidoc.element.postcss-cssnext.warn_for_duplicates.default)
- description and source-code
```javascript
function creator() {
  var transformer = initializer.apply(undefined, arguments);
  transformer.postcssPlugin = name;
  transformer.postcssVersion = new _processor2.default().version;
  return transformer;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
