# npmtest-ftp-deploy

#### test coverage for  [ftp-deploy (v1.2.0)](https://github.com/rickbergfalk/ftp-deploy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ftp-deploy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ftp-deploy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ftp-deploy.svg)](https://travis-ci.org/npmtest/node-npmtest-ftp-deploy)

#### Ftp a folder from your local disk to an ftp destination. Does not delete from destination directory. Derived from grunt-ftp-deploy

[![NPM](https://nodei.co/npm/ftp-deploy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ftp-deploy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ftp-deploy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ftp-deploy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ftp-deploy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ftp-deploy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ftp-deploy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ftp-deploy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ftp-deploy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ftp-deploy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ftp-deploy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ftp-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ftp-deploy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ftp-deploy/build/test-report.html](https://npmtest.github.io/node-npmtest-ftp-deploy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ftp-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ftp-deploy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ftp-deploy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ftp-deploy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ftp-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ftp-deploy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ftp-deploy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ftp-deploy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rick Bergfalk",
        "url": "http://rickbergfalk.com/"
    },
    "bugs": {
        "url": "https://github.com/rickbergfalk/ftp-deploy/issues"
    },
    "contributors": [
        {
            "name": "Ondrej",
            "url": "https://github.com/der-On"
        },
        {
            "name": "keyle",
            "url": "https://github.com/keyle"
        }
    ],
    "dependencies": {
        "async": "1.x.x",
        "jsftp": "1.x.x",
        "minimatch": "0.2.12",
        "read": "1.0.5"
    },
    "description": "Ftp a folder from your local disk to an ftp destination. Does not delete from destination directory. Derived from grunt-ftp-deploy",
    "devDependencies": {
        "xo": "^0.18.1"
    },
    "directories": {},
    "dist": {
        "shasum": "552a63fa47756947bb8d8c4321722228343eb3d0",
        "tarball": "https://registry.npmjs.org/ftp-deploy/-/ftp-deploy-1.2.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "75c2856a9210501a4cc842b62cccd136307fd23d",
    "homepage": "https://github.com/rickbergfalk/ftp-deploy#readme",
    "keywords": [
        "ftp",
        "deploy"
    ],
    "main": "ftp-deploy",
    "maintainers": [
        {
            "name": "rickbergfalk"
        }
    ],
    "name": "ftp-deploy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/rickbergfalk/ftp-deploy.git"
    },
    "scripts": {
        "lint": "xo",
        "lint-fix": "xo --fix",
        "test": "node test/test.js"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
