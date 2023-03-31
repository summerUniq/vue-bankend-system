# vue-bankend-system

使用 vue3 + typescript + element 搭建的后台管理系统

# 项目搭建

- 局部使用@vue-cli 初始化项目

```
cnpm i -D @vue/cli
npx vue create project-one
```

- 修改项目配置,自动打开网页

vue.config.js 进行修改

```
const { defineConfig } = require('@vue/cli-service')
module.exports = defineConfig({
  transpileDependencies: true,
  devServer: {
    open: true,
    host: 'localhost'
  }
})
```

- vue-cli ui 的使用

```
npx vue ui
```
