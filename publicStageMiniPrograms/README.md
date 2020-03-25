<!--
 * @Author: your name
 * @Date: 2020-03-20 15:23:03
 * @LastEditTime: 2020-03-20 16:02:48
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /taro-project/publicStageMiniPrograms/README.md
 -->
## 笔者开发环境简介：
>macOS 10.13.5
>node 版本：10.18.0
>npm 版本：6.13.4
>yarn 版本：1.22.4

## Taro简介
  Taro 是一款遵循`React`规范的`多端开发`解决方案。
## 安装
* 安装`Taro` 开发工具 `@tarojs/cli`
* 可以使用 `npm` 或者 `yarn` 进行全局安装,或者直接使用`npx`
* `npm install -g @tarojs/cli`
* `yarn global add @tarojs/cli`

在终端中输入:
```shell
yarn global add @tarojs/cli
```
出现下面信息说明安装成功
```shell
 [4/4] 🔨  Building fresh packages...
success Installed "@tarojs/cli@2.0.7" with binaries:
      - taro
✨  Done in 59.96s.
```
## 使用 
使用命令创建模板项目
```shell
taro init taro init publicStageMiniPrograms
```

>👽 Taro v2.0.7
当前您正在使用 Taro 2.0 版本，请先执行 taro doctor 确保编译配置正确
如出现令你束手无策的问题，请使用 taro update 命令更新到你指定的稳定版本
Taro 即将创建一个新项目!
Need help? Go and open issue: https://github.com/NervJS/taro/issues/new

看到上面的提示信息说明已经初始化成功了

✔ 拉取远程模板仓库成功！
? 请输入项目介绍！ 橙分期小程序
? 是否需要使用 TypeScript ？ No
? 请选择 CSS 预处理器（Sass/Less/Stylus） Less
? 请选择模板 默认模板

需要我们写一个初始化的信息，这里选用的是 less 和默认模板 没有使用typescript

cd publicStageMiniPrograms 进入项目目录

执行 yarn dev:h5 开始预览 h5 端的代码


#### 开发期间启动的命令
npm run dev:h5 web
npm run dev:weapp 微信小程序
npm run dev:aliapy 支付宝小程序
npm run dev:swan 百度小程序
npm run dev:rn ReactNative

#### 编译期间命令
npm run build:h5 web
npm run build:weapp 微信小程序
npm run build:aliapy 支付宝小程序
npm run build:swan 百度小程序
npm run build:rn ReactNative

## 框架的目录结构
dist 编译结果目录
config 配置目录
  dev.js 开发时候配置
  index.js 默认配置
  prod.js 打包时候配置
src 
  pages   页面文件目录
    index index 页面目录
      index.js index页面逻辑
      index.css index 页面样式
  app.css  项目总通用样式
  app.js   项目入口文件
package.json 

