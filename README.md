# npmtest-minimize

#### basic test coverage for  [minimize (v2.1.0)](https://github.com/Moveo/minimize#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-minimize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-minimize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-minimize.svg)](https://travis-ci.org/npmtest/node-npmtest-minimize)

#### Minimize HTML

[![NPM](https://nodei.co/npm/minimize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minimize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-minimize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-minimize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-minimize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-minimize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-minimize/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-minimize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-minimize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-minimize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-minimize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-minimize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-minimize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-minimize/build/test-report.html](https://npmtest.github.io/node-npmtest-minimize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-minimize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-minimize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-minimize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minimize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minimize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minimize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-minimize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-minimize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Martijn Swaagman"
    },
    "bin": {
        "minimize": "./bin/minimize"
    },
    "bugs": {
        "url": "https://github.com/Moveo/minimize/issues"
    },
    "dependencies": {
        "argh": "^0.1.4",
        "async": "^2.1.5",
        "cli-color": "^1.2.0",
        "diagnostics": "^1.1.0",
        "emits": "^3.0.0",
        "htmlparser2": "^3.9.2",
        "uuid": "^3.0.0"
    },
    "description": "Minimize HTML",
    "devDependencies": {
        "chai": "^3.5.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "pre-commit": "^1.2.2",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fa277647fc5f9a21524bfde62814ca7ce1ffd7a2",
        "tarball": "https://registry.npmjs.org/minimize/-/minimize-2.1.0.tgz"
    },
    "gitHead": "67713aa6182941edb53f24598b700349812fb8d5",
    "homepage": "https://github.com/Moveo/minimize#readme",
    "keywords": [
        "minify",
        "minimize",
        "HTML"
    ],
    "license": "MIT",
    "main": "./lib/minimize",
    "maintainers": [
        {
            "name": "swaagie"
        }
    ],
    "name": "minimize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Moveo/minimize.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- $(find test -name '*.test.js')",
        "test": "mocha $(find test -name '*.test.js')",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- $(find test -name '*.test.js')",
        "watch": "mocha --watch $(find test -name '*.test.js')"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
