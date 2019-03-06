# yaoboliu-vueProjectbuild

> A Vue.js project

## Build Setup

``` bash
# 安装依赖
npm install

# 本地运行 localhost:8080
npm run dev

# 打包压缩
npm run build

# 打包压缩，并输出日志
npm run build --report
```
### 由于vue已经更新到3.0，所以需要按照以下步骤操作,才可以使用vue init搭建项目：
#### 1.安装全局的vue: `npm install -g @vue/cli `或者`yarn global add @vue/cli`，
#### 2.使用vue create project-name,创建一个项目文件夹,此处可以选择默认的项目配置（default），也可以按需求选择项目配置项（Manually select features），
#### 3.如果想要使用旧版的`vue init`来创建一个项目文件夹，需要全局安装一个桥接工具`npm install -g @vue/cli-init`,然后执行`vue init webpack project-name`。

详细了解 [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
