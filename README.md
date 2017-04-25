# npmtest-spritesmith

#### basic test coverage for  [spritesmith (v3.1.1)](https://github.com/Ensighten/spritesmith)  [![npm package](https://img.shields.io/npm/v/npmtest-spritesmith.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spritesmith) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spritesmith.svg)](https://travis-ci.org/npmtest/node-npmtest-spritesmith)

#### Utility that takes images and creates a spritesheet with JSON sprite data

[![NPM](https://nodei.co/npm/spritesmith.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spritesmith)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spritesmith/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spritesmith/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spritesmith/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spritesmith/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spritesmith/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-spritesmith/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-spritesmith/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spritesmith/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spritesmith/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-spritesmith/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-spritesmith/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spritesmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-spritesmith/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-spritesmith/build/test-report.html](https://npmtest.github.io/node-npmtest-spritesmith/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-spritesmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spritesmith/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-spritesmith/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spritesmith/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spritesmith/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spritesmith/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spritesmith/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spritesmith/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Todd Wolfson",
        "url": "http://twolfson.com/"
    },
    "bugs": {
        "url": "https://github.com/Ensighten/spritesmith/issues"
    },
    "contributors": [
        {
            "name": "Alex Bain"
        }
    ],
    "dependencies": {
        "concat-stream": "~1.5.1",
        "layout": "~2.2.0",
        "pixelsmith": "~2.1.0",
        "semver": "~5.0.3",
        "through2": "~2.0.0"
    },
    "description": "Utility that takes images and creates a spritesheet with JSON sprite data",
    "devDependencies": {
        "canvassmith": "~1.0.0",
        "foundry": "~4.3.2",
        "foundry-release-git": "~2.0.2",
        "foundry-release-npm": "~2.0.2",
        "get-pixels": "~3.1.0",
        "jscs": "~1.8.1",
        "jshint": "~2.5.10",
        "mocha": "~1.21.4",
        "phantomjssmith": "~1.0.0",
        "twolfson-style": "~1.6.0",
        "vinyl": "~1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4e5364eb9bfd987daf6c1b48a58d2be5b6a0f8d7",
        "tarball": "https://registry.npmjs.org/spritesmith/-/spritesmith-3.1.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "foundry": {
        "releaseCommands": [
            "foundry-release-git",
            "foundry-release-npm"
        ]
    },
    "gitHead": "96216e3e4c19273c7ea8578f2f04a9a73e1bb92e",
    "homepage": "https://github.com/Ensighten/spritesmith",
    "keywords": [
        "sprite",
        "spritesheet",
        "css"
    ],
    "license": "MIT",
    "main": "src/smith.js",
    "maintainers": [
        {
            "name": "twolfson"
        }
    ],
    "name": "spritesmith",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Ensighten/spritesmith.git"
    },
    "scripts": {
        "lint": "twolfson-style lint src/ src-test/",
        "precheck": "twolfson-style precheck src/ src-test/",
        "pretest": "twolfson-style install",
        "test": "npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint"
    },
    "version": "3.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
