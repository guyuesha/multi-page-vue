# Basic multi-page vue project

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080,
# get the page by localhost:8080/module/pagename.html
npm run dev

# build for production with minification
npm run build

# 使用[node模块](https://github.com/jprichardson/node-fs-extra)进行模板文件的创建复制及重命名操作
# 参考[node API](http://nodejs.cn/api/fs.html) pagename参数不可缺少且不能与现有module名称重复，否则报错
node makefile.js pagename
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
