# npmtest-jsinspect

#### basic test coverage for  [jsinspect (v0.12.4)](https://github.com/danielstjules/jsinspect)  [![npm package](https://img.shields.io/npm/v/npmtest-jsinspect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsinspect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsinspect.svg)](https://travis-ci.org/npmtest/node-npmtest-jsinspect)

#### Detect structural similarities in your code

[![NPM](https://nodei.co/npm/jsinspect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsinspect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsinspect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsinspect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsinspect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsinspect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsinspect/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsinspect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsinspect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsinspect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsinspect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsinspect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsinspect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsinspect/build/test-report.html](https://npmtest.github.io/node-npmtest-jsinspect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsinspect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsinspect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsinspect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsinspect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsinspect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsinspect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsinspect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsinspect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel St. Jules"
    },
    "bin": {
        "jsinspect": "./bin/jsinspect"
    },
    "bugs": {
        "url": "https://github.com/danielstjules/jsinspect/issues"
    },
    "dependencies": {
        "babylon": "6.16.1",
        "chalk": "*",
        "commander": "*",
        "filepaths": "0.3.0",
        "stable": "0.1.6",
        "strip-indent": "^1.0.0",
        "strip-json-comments": "1.0.2"
    },
    "description": "Detect structural similarities in your code",
    "devDependencies": {
        "concat-stream": "^1.5.0",
        "dirmap": "0.0.2",
        "expect.js": "*",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f1f8258678d9994ac90629985c227d121874c768",
        "tarball": "https://registry.npmjs.org/jsinspect/-/jsinspect-0.12.4.tgz"
    },
    "gitHead": "019b0bf33d3ff23dc9b9f5c2e6170bcde6f66b18",
    "homepage": "https://github.com/danielstjules/jsinspect",
    "keywords": [
        "inspect",
        "detect",
        "code",
        "duplicate",
        "structure",
        "copy",
        "paste"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "danielstjules"
        }
    ],
    "name": "jsinspect",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danielstjules/jsinspect.git"
    },
    "scripts": {
        "test": "mocha -R spec spec spec/reporters"
    },
    "version": "0.12.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
