# test coverage for  [hummus (v1.0.75)](http://pdfhummus.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-hummus.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hummus) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hummus.svg)](https://travis-ci.org/npmtest/node-npmtest-hummus)
#### Create, read and modify PDF files and streams

[![NPM](https://nodei.co/npm/hummus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hummus)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hummus/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hummus/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hummus/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hummus/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hummus/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hummus/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hummus/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hummus/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hummus/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hummus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hummus/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hummus/build/test-report.html](https://npmtest.github.io/node-npmtest-hummus/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hummus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hummus/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hummus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hummus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hummus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hummus/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hummus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hummus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gal Kahana"
    },
    "binary": {
        "module_name": "hummus",
        "module_path": "./binding",
        "remote_path": "./{module_name}/v{version}/{toolset}/",
        "host": "https://hummus.s3-us-west-2.amazonaws.com",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz"
    },
    "bugs": {
        "url": "https://github.com/galkahana/HummusJS/issues"
    },
    "bundleDependencies": [
        "node-pre-gyp"
    ],
    "dependencies": {
        "node-pre-gyp": "^0.6.13"
    },
    "description": "Create, read and modify PDF files and streams",
    "devDependencies": {
        "aws-sdk": "~2.0.0-rc.15",
        "chai": "^3.4.0",
        "mocha": "^2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "746d8fb4e819c84ef8092dabf426f620b81cc22e",
        "tarball": "https://registry.npmjs.org/hummus/-/hummus-1.0.75.tgz"
    },
    "files": [
        "src",
        "hummus.js",
        "binding.gyp",
        "PDFRStreamForFile.js",
        "PDFStreamForResponse.js",
        "PDFWStreamForFile.js"
    ],
    "gitHead": "7d6dce6cab997af0860b1000c5616405073aab97",
    "homepage": "http://pdfhummus.com/",
    "keywords": [
        "pdf",
        "pdfhummus"
    ],
    "license": "Apache-2.0",
    "main": "./hummus.js",
    "maintainers": [
        {
            "name": "galkahana"
        }
    ],
    "name": "hummus",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/galkahana/HummusJS.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "test": "mocha -R tap ./tests/*.js --timeout 15000"
    },
    "version": "1.0.75"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
