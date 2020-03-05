# vue_demo

> 学习vue：vue示例

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

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

build   -------------------项目构建相关代码（webpack配置）
    build.js  -------------生产环境构建代码
    check-versions.js  ----检查node、npm等版本
    utils.js  -------------构建工具相关
    vue-loader.conf.js  ----css加载器的配置
    webpack.base.conf.js  ---webpack的基础配置信息
    webpack.dev.conf.js  ----webpack开发环境配置信息，构建开发本地服务器
    webpack.prod.conf.js  ---wenpack生产环境配置信息
config  -------------------配置目录，包括端口号，打包输出等的vue基本配置文件
    dev.env.js  -----------开发环境变量
    prod.env.js -----------生产环境变量
    index.js  -------------项目的配置变量，端口号等 
node_modules    -----------加载的项目依赖模块
static  -------------------静态资源目录
index.html  ---------------首页的入口文件，可以添加meta等参数
README.md   ---------------项目的说明文档，makedown格式
src -----------------------源码目录，主要的开发
    assets  ---------------静态资源，css,image等可以存放
    components  -----------公共组件
    router  ---------------路由文件夹，配置页面跳转
    views  ----------------页面编写的地方，（可以自行定义命名）
main.js  ------------------入口文件，全局的配置和加载
.babelrc  -----------------ES6语法编译配置，用来将es6代码转换成浏览器可识别的es5代码
.gitignore  ---------------git上传需要忽略的文件的格式
package.json  -------------项目的基本信息，包括开发所需要的模块、项目名称、版本号等
.postcssrc.js  ------------转换css的工具
.editorconfig  ------------定义代码格式
