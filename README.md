# npmtest-cloudcmd

#### basic test coverage for  [cloudcmd (v6.9.3)](http://cloudcmd.io)  [![npm package](https://img.shields.io/npm/v/npmtest-cloudcmd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cloudcmd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cloudcmd.svg)](https://travis-ci.org/npmtest/node-npmtest-cloudcmd)

#### Orthodox web file manager with console and editor

[![NPM](https://nodei.co/npm/cloudcmd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cloudcmd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cloudcmd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cloudcmd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cloudcmd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cloudcmd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cloudcmd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cloudcmd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cloudcmd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cloudcmd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cloudcmd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cloudcmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cloudcmd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cloudcmd/build/test-report.html](https://npmtest.github.io/node-npmtest-cloudcmd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cloudcmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cloudcmd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cloudcmd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cloudcmd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloudcmd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloudcmd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cloudcmd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cloudcmd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "coderaiser",
        "url": "https://github.com/coderaiser"
    },
    "bin": {
        "cloudcmd": "legacy/bin/cloudcmd.js",
        "cloudcmd+": "bin/cloudcmd.js"
    },
    "bugs": {
        "url": "https://github.com/coderaiser/cloudcmd/issues"
    },
    "config": {
        "dirs": "bin server test webpack.config.js"
    },
    "dependencies": {
        "apart": "^1.0.1",
        "chalk": "^1.1.0",
        "checkup": "^1.3.0",
        "console-io": "^3.0.0",
        "copymitter": "^2.0.0",
        "criton": "^1.0.0",
        "currify": "^2.0.3",
        "deepmerge": "^1.3.2",
        "deepword": "^1.3.0",
        "dword": "^4.1.0",
        "edward": "^4.2.0",
        "execon": "^1.2.0",
        "express": "^4.13.0",
        "files-io": "^1.2.0",
        "flop": "^2.0.0",
        "format-io": "^0.9.6",
        "http-auth": "^2.3.1",
        "inly": "^1.0.2",
        "ishtar": "^1.5.0",
        "jaguar": "^3.0.0",
        "jju": "^1.3.0",
        "join-io": "^1.4.0",
        "jonny": "^1.0.0",
        "markdown-it": "^8.0.0",
        "mellow": "^2.0.0",
        "minify": "^2.0.0",
        "minimist": "^1.2.0",
        "mollify": "^1.0.0",
        "nomine": "^1.0.1",
        "omnes": "^1.0.3",
        "onezip": "^1.0.5",
        "opn": "^4.0.1",
        "os-homedir": "^1.0.0",
        "package-json": "^2.3.0",
        "ponse": "^1.4.0",
        "pullout": "^1.0.1",
        "remedy": "^1.5.0",
        "rendy": "^1.1.0",
        "restafary": "^2.0.0",
        "salam": "^1.0.0",
        "socket.io": "^1.4.3",
        "spero": "^1.5.0",
        "squad": "^1.1.3",
        "try-catch": "^1.0.0",
        "tryrequire": "^1.1.5",
        "writejson": "^1.1.0"
    },
    "description": "Orthodox web file manager with console and editor",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-loader": "^6.2.10",
        "babel-plugin-transform-object-assign": "^6.22.0",
        "babel-preset-es2015": "^6.18.0",
        "coveralls": "^2.11.6",
        "emitify": "^2.1.1",
        "es6-promise": "^4.0.5",
        "es6-promisify": "^5.0.0",
        "eslint": "^3.1.1",
        "gunzip-maybe": "^1.3.1",
        "jscs": "^3.0.1",
        "jshint": "^2.8.0",
        "minor": "^1.2.2",
        "mkdirp": "^0.5.1",
        "morgan": "^1.6.1",
        "nodemon": "^1.9.1",
        "nsp": "^2.2.1",
        "nyc": "^10.1.2",
        "place": "^1.1.4",
        "readjson": "^1.1.3",
        "recess": "^1.1.9",
        "redrun": "^5.0.0",
        "request": "^2.76.0",
        "rimraf": "^2.5.4",
        "shortdate": "^1.0.1",
        "sinon": "^2.1.0",
        "sinon-called-with-diff": "^1.0.0",
        "socket.io-client": "^1.5.1",
        "stylelint": "^7.0.2",
        "stylelint-config-standard": "^16.0.0",
        "tape": "^4.4.0",
        "tar-stream": "^1.5.2",
        "version-io": "^1.2.5",
        "webpack": "^2.2.1",
        "wraptile": "^1.0.0",
        "yaspeller": "^3.0.0"
    },
    "directories": {
        "man": "man"
    },
    "dist": {
        "shasum": "5a0a00632fc85bb296def6611768d351afe12898",
        "tarball": "https://registry.npmjs.org/cloudcmd/-/cloudcmd-6.9.3.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "d20128add5b4753489f54fac80b2e8c227dc5b54",
    "homepage": "http://cloudcmd.io",
    "keywords": [
        "console",
        "edit",
        "editor",
        "file",
        "file manager",
        "folder",
        "orthodox",
        "view",
        "viewer",
        "copy",
        "rename",
        "move",
        "rm",
        "mv",
        "cp",
        "delete",
        "delete file",
        "delete directory",
        "remove",
        "remove file",
        "remove directory",
        "file operation",
        "pack",
        "server"
    ],
    "license": "MIT",
    "main": "legacy/server/cloudcmd.js",
    "maintainers": [
        {
            "name": "coderaiser"
        }
    ],
    "man": [
        "/home/coderaiser/cloudcmd/man/cloudcmd.1"
    ],
    "name": "cloudcmd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/coderaiser/cloudcmd.git"
    },
    "scripts": {
        "6to5:bin": "babel bin -d legacy/bin",
        "6to5:client": "webpack --progress",
        "6to5:client:dev": "NODE_ENV=development redrun 6to5:client",
        "6to5:server": "babel server -d server_",
        "build": "redrun rm:* 6to5:* mkdir:* legacy:*",
        "build:client": "redrun 6to5:client",
        "build:client:dev": "redrun 6to5:client:dev",
        "codestyle": "redrun lint spell",
        "coverage": "nyc npm test",
        "docker": "redrun docker:pull* docker:build* docker:tag* docker:push*",
        "docker:alpine": "redrun docker:pull:alpine docker:build:alpine docker:tag:alpine docker:push:alpine docker:push:alpine:latest",
        "docker:build": "docker build -t coderaiser/cloudcmd:'version' .",
        "docker:build:alpine": "docker build -f Dockerfile.alpine -t coderaiser/cloudcmd:'version'-alpine .",
        "docker:pull:alpine": "docker pull mhart/alpine-node",
        "docker:pull:node": "docker pull node",
        "docker:push": "docker push coderaiser/cloudcmd:'version'",
        "docker:push:alpine": "docker push coderaiser/cloudcmd:'version'-alpine",
        "docker:push:alpine:latest": "docker push coderaiser/cloudcmd:latest-alpine",
        "docker:rm-old": "redrun --parallel docker:rm:*",
        "docker:rm:alpine": "docker rmi coderaiser/cloudcmd:'version'-alpine",
        "docker:rm:latest": "docker rmi coderaiser/cloudcmd:latest",
        "docker:rm:latest-alpine": "docker rmi coderaiser/cloudcmd:latest-alpine",
        "docker:rm:version": "docker rmi coderaiser/cloudcmd:'version'",
        "docker:tag:alpine": "docker tag coderaiser/cloudcmd:'version'-alpine coderaiser/cloudcmd:latest-alpine",
        "fix:js:eslint:client": "redrun eslint:client -- --fix",
        "fix:js:eslint:server": "redrun eslint:server -- --fix",
        "heroku-postbuild": "redrun 6to5:client -- --progress && npm i gritty",
        "legacy:help": "cp json/help.json legacy/json/",
        "legacy:package": "echo \"module.exports = require('../package');\" > legacy/package.js",
        "legacy:server": "bin/legacy.js",
        "lint": "redrun lint:*",
        "lint:css": "recess css/*.css",
        "lint:js": "redrun lint:js:*",
        "lint:js:eslint:client": "eslint --rule 'no-console:0' --env browser client",
        "lint:js:eslint:server": "eslint --rule 'no-console:0' $npm_package_config_dirs",
        "lint:js:jscs": "jscs --esnext $npm_package_config_dirs",
        "lint:js:jshint": "jshint bin client server",
        "lint:style": "stylelint css/*.css",
        "mkdir:json": "mkdirp legacy/json",
        "mkdir:server": "mkdirp legacy/server",
        "postpublish": "redrun docker",
        "report": "nyc report --reporter=text-lcov | coveralls",
        "rm:client": "rimraf dist dist-dev",
        "rm:server": "rimraf server_ legacy",
        "security": "nsp check",
        "spell": "yaspeller .",
        "start": "node bin/cloudcmd.js",
        "start:dev": "NODE_ENV=development node bin/cloudcmd.js",
        "test": "tape 'test/**/*.js'",
        "w:c": "redrun watch:client",
        "w:c:d": "redrun watch:client:dev",
        "watch:client": "redrun 6to5:client -- --watch",
        "watch:client:dev": "redrun 6to5:client:dev -- --watch",
        "watch:coverage": "nodemon -w server -w test -w common -x \"npm run coverage\"",
        "watch:lint": "nodemon -w client -w server -w webpack.config.js -x 'redrun lint:js'",
        "watch:lint:client": "nodemon -w client -w webpack.config.js -x 'redrun lint:js:eslint:client'",
        "watch:server": "nodemon bin/cloudcmd.js",
        "watch:test": "nodemon -w server -w test -w common -x \"npm run test\"",
        "wisdom": "npm run build; npm run docker:rm-old; bin/release.js"
    },
    "subdomain": "cloudcmd",
    "version": "6.9.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
