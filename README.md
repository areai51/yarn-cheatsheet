# Yarn Cheatsheet


## Why Yarn
### Yarn is Super Fast!!
Yarn caches every package it downloads so it never needs to again. It also parallelizes operations to maximize resource utilization so install times are faster than ever.


## Common NPM commands in Yarn

|NPM Command | Yarn Command| Description (_wherever necessary_)|
|:---|:---|---|
|npm install|yarn  <br/> yarn install|Will install packages listed in the package.json file|
| npm install `pkg-name` <br/> npm install --save `pkg-name`| yarn add `pkg-name`|By default Yarn  adds the pgk-name to package.json and yarn.lock files|
|npm install  `pkg-name@1.0.0` | yarn add `pgk-name@1.0.0`|
|npm  install `pkg-name` --dev| yarn add --dev|  
|npm  install `pkg-name` --peer| yarn add --peer|  
|npm  install `pkg-name` --optional| yarn add --optional|  
|npm install -g `pkg-name`|yarn add global `pkg-name`|
|npm update | yarn upgrade|Note its called **upgrade** in yarn
|npm uninstall `pkg-name`| yarn remove `pkg-name`|
|npm run `scrit-name`| yarn run `script-name`|
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



### New Commands in Yarn
|Yarn Command | Description|
|---|---|
|yarn why `pkg-name` | Builds a dependency gaph on why this package is being used.|
|yarn clean | frees up space by removing unnecessary files and folders from dependencies|
|yarn licenses ls | Inspect the licenses of your dependencies |
yarn licenses generate-disclaimer | Automatically create your license dependency disclaimer|




## References
https://yarnpkg.com/en/docs/
