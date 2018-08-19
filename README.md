# traveling

> 旅游App

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



# 项目学习过程总结
  ##git版本管理工具入门使用方法
``` bash
    使用git将项目上传到github（最简单方法）学习地址：https://www.cnblogs.com/cxk1995/p/5800196.html
```
## 知识点：
``` bash
    1.webpack.base.conf.js  修改配置文件
     alias: {
      'vue$': 'vue/dist/vue.esm.js',
      '@': resolve('src'),
      'styles':resolve('src/assets/styles')
    }
 作用：import 'styles/iconfont.css' 
 意义：重新配置了webpack.base.conf.js文件，这样可以减少import文件的代码
 ```
