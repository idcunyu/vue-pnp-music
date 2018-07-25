# vue-pnp-music

> Pineapple - PNP - 音乐播放器

## 项目结构

- API
- 公共资源：src/common文件夹内，包含文字类型fonts、图片image、js、预编译stylus 等。
- 组件库
  - /src/base目录中的基础组件库，在正式项目或大型项目可以放到npm的一个模块，然后通过npm安装这个依赖；
  - /src/components目录中的业务组件库。
- router：路由
- store：数据管理

## Build Setup

``` bash
# npm or cnpm
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
