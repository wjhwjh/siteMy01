# my01

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

-----------------------------------------
遇到问题如何处理，如何思考这个问题，解决的方法，要达到的目的是什么，目前自己的状态

相关知识问题

1. vue项目里static文件和assets文件的区别

static文件夹是存放静态文件的， 可以直接引入

assets中的文件夹中的文件是以模块形式打包的， 也就是需要以模块形式引入， 图片、css、js都得用import模块的形式引入

2. mintUI中使用细节

tabbar结合路由实现跳转

路由

linkActiveClass 使用
---路由对象中的一个属性
new Router({
linkActiveClass:'link-active',
[
{},
{},
...
]
})

路由中导航式编程

this.$router.go(-1); // 返回上一级

3. 时间的处理

vue里过滤器处理时间



















