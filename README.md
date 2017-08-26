
<img src="https://cdn.rawgit.com/detailyang/awesome-cheatsheet/master/awesome.svg" alt="awesome" width="120" align="right" >

# Awesome Cheatsheet [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/detailyang/awesome-cheatsheet)

![Branch master](https://img.shields.io/badge/branch-master-brightgreen.svg?style=flat-square)    [![Build Status](https://api.travis-ci.org/detailyang/awesome-cheatsheet.svg)](https://travis-ci.org/detailyang/awesome-cheatsheet)    [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/detailyang/awesome-cheatsheet/master/LICENSE)


## Why Yarn

### Yarn is Super Fast!!
Yarn caches every package it downloads so it never needs to again. It also parallelizes operations to maximize resource utilization so install times are faster than ever.


## Common NPM commands in Yarn

|NPM Command | Yarn Command| Description (_wherever necessary_)|
|:---|:---|---|
|npm install|yarn <br/> yarn install|Will install packages listed in the `package.json` file|
|npm install `pkg-name` <br/> npm install --save `pkg-name`| yarn add `pkg-name`|By default Yarn adds the `pgk-name` to `package.json` and `yarn.lock` files|
|npm install `pkg-name@1.0.0` | yarn add `pgk-name@1.0.0`|
|npm install `pkg-name` --save-dev| yarn add `pkg-name` --dev|
|npm install `pkg-name` --peer| yarn add `pkg-name`--peer|
|npm install `pkg-name` --optional| yarn add --optional|
|npm install -g `pkg-name`| yarn global add `pkg-name`| Careful, yarn add global `pkg-name` adds packages `global` and `pkg-name` locally! |
|npm update | yarn upgrade| Note: It's called **upgrade** in yarn|
|npm uninstall `pkg-name`| yarn remove `pkg-name`|
|npm run `script-name`| yarn run `script-name`|
|npm init | yarn init|
|npm pack | yarn pack| Creates a compressed gzip archive of the package dependencies|
|npm link | yarn link|
|npm outdated | yarn outdated|
|npm publish | yarn publish|
|npm run | yarn run|
|npm cache clean | yarn cache clean|
|npm login | yarn login (and logout)|
|npm test | yarn test|
|npm install --production | yarn --production|
|npm  --version | yarn version|
|npm  info | yarn info|


### New Commands in Yarn
|Yarn Command | Description|
|---|---|
|yarn why `pkg-name` | Builds a dependency graph on why this package is being used|
|yarn clean | Frees up space by removing unnecessary files and folders from dependencies|
|yarn licenses ls | Inspect the licenses of your dependencies|
|yarn licenses generate-disclaimer | Automatically create your license dependency disclaimer|


## References
https://yarnpkg.com/en/docs/
