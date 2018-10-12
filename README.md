# maijia

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
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

转多页面应用
1. 调整目录
    1. index.html放到src目录里
    2. src目录下添加modules，pages，index文件夹
    3. main.js改名为index.js
    4. 移动assets，router,app.vue,index.html,index.js到index文件夹
    5. index文件夹移动到pages文件夹
2. webpack配置
    1. build/utils.js 修改，添加