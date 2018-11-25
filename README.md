# electron

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```
# package.json配置Mac系统
"package": "electron-packager ./ dsk --arch=x64 --out ./ " 
# package.json配置android系统
"package": "electron-packager ./ dsk --platform=win32 --arch=x64 --out ./ " 

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
